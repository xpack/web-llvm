---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bfi-detail/irreduciblegraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IrreducibleGraph` Struct Reference

<p>Graph of irreducible control flow. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::bfi_detail::IrreducibleGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a281c4629c5f31af3afd60c42fbd93f6b">BFIBase</a> = <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase">BlockFrequencyInfoImplBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f2854e822f1b323869fb6c7ae6fc0d0">BlockNode</a> = <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode">BFIBase::BlockNode</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockEdgesAdder&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1147f0ef1ac705077e24462022b4ae1e">IrreducibleGraph</a> (BFIBase &amp;BFI, const BFIBase::LoopData *OuterLoop, BlockEdgesAdder addBlockEdges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an explicit graph containing irreducible control flow. <a href="#a1147f0ef1ac705077e24462022b4ae1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockEdgesAdder&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a> (const BFIBase::LoopData *OuterLoop, BlockEdgesAdder addBlockEdges)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add4c9ca63093a8270248e72b08c5302e">addNodesInLoop</a> (const BFIBase::LoopData &amp;OuterLoop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0299c4b86be9e4857e810b2160f37cf7">addNodesInFunction</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98ee11535062e1034345efac121ec05">addNode</a> (const BlockNode &amp;Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1377985f15180a3717b4a519b13eaedb">indexNodes</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BlockEdgesAdder&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d4ad30cd1d596501e3d99462d1af74e">addEdges</a> (const BlockNode &amp;Node, const BFIBase::LoopData *OuterLoop, BlockEdgesAdder addBlockEdges)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17262e1cca3f9a69224d04b3189ed90c">addEdge</a> (IrrNode &amp;Irr, const BlockNode &amp;Succ, const BFIBase::LoopData *OuterLoop)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a281c4629c5f31af3afd60c42fbd93f6b">BFIBase</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b13aeab236aa95632c9ef9052c14926">BFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a4f2854e822f1b323869fb6c7ae6fc0d0">BlockNode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2780a8fb8a885011f9d14494c5c8dc">Start</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/irrnode">IrrNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b2037773f618188c79aec1444116647">StartIrr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/irrnode">IrrNode</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8961714adf03d003152f5f785da8b26a">Nodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; uint32_t, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/irrnode">IrrNode</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0e48b4d74e4dbcd777495cd16ae822">Lookup</a></td>
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

<p>Graph of irreducible control flow.</p>


<p>This graph is used for determining the SCCs in a loop (or top-level function) that has irreducible control flow.</p>


<p>During the block frequency algorithm, the local graphs are defined in a light-weight way, deferring to the <em><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a></em> or <em><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></em> graphs for most edges, but getting others from <em>LoopData::ExitMap</em>. The latter only has successor information.</p>


<p><em><a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph">IrreducibleGraph</a></em> makes this graph explicit. It's in a form that can use <em><a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a></em> (so that <em>analyzeIrreducible()</em> can use <em><a href="/web-llvm/docs/api/classes/llvm/scc-iterator">scc_iterator</a></em>), and it explicitly lists predecessors and successors. The initialization that relies on <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></span> is defined in the header.</p>


<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BFIBase {#a281c4629c5f31af3afd60c42fbd93f6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bfi_detail::IrreducibleGraph::BFIBase =  BlockFrequencyInfoImplBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

### BlockNode {#a4f2854e822f1b323869fb6c7ae6fc0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bfi_detail::IrreducibleGraph::BlockNode =  BFIBase::BlockNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IrreducibleGraph() {#a1147f0ef1ac705077e24462022b4ae1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockEdgesAdder&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::bfi_detail::IrreducibleGraph::IrreducibleGraph (<a href="#a281c4629c5f31af3afd60c42fbd93f6b">BFIBase</a> &amp; BFI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">BFIBase::LoopData</a> * OuterLoop, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/blockedgesadder">BlockEdgesAdder</a> addBlockEdges)</td>
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

<p>Construct an explicit graph containing irreducible control flow.</p>


<p>Construct an explicit graph of the control flow in <span class="doxyComputerOutput">OuterLoop</span> (or the top-level function, if <span class="doxyComputerOutput">OuterLoop</span> is <span class="doxyComputerOutput">nullptr</span>). Uses <span class="doxyComputerOutput">addBlockEdges</span> to add block successors that have not been packaged into loops.</p>


<p><em>BlockFrequencyInfoImpl::computeIrreducibleMass()</em> is the only expected user of this.</p>


<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a3b13aeab236aa95632c9ef9052c14926">BFI</a> and <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addEdge() {#a17262e1cca3f9a69224d04b3189ed90c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IrreducibleGraph::addEdge (<a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/irrnode">IrrNode</a> &amp; Irr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4f2854e822f1b323869fb6c7ae6fc0d0">BlockNode</a> &amp; Succ, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">BFIBase::LoopData</a> * OuterLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/irrnode/#ae21e5d7ba9e61bdd5a1b97cf142fbaa1">llvm::bfi_detail::IrreducibleGraph::IrrNode::Edges</a>, <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/blocknode/#afd6ff190a72a58d7c890cf480bc6f6e8">llvm::BlockFrequencyInfoImplBase::BlockNode::Index</a>, <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata/#a0f46dabedb551531591c0293403c7e21">llvm::BlockFrequencyInfoImplBase::LoopData::isHeader</a>, <a href="#aae0e48b4d74e4dbcd777495cd16ae822">Lookup</a> and <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/irrnode/#afa65e9330ea446ed6f3b50dcefd93905">llvm::bfi_detail::IrreducibleGraph::IrrNode::NumIn</a>.</p>


<p>Referenced by <a href="#a2d4ad30cd1d596501e3d99462d1af74e">addEdges</a>.</p>

</div>
</div>

### addEdges() {#a2d4ad30cd1d596501e3d99462d1af74e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockEdgesAdder&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::bfi_detail::IrreducibleGraph::addEdges (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4f2854e822f1b323869fb6c7ae6fc0d0">BlockNode</a> &amp; Node, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">BFIBase::LoopData</a> * OuterLoop, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/blockedgesadder">BlockEdgesAdder</a> addBlockEdges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a17262e1cca3f9a69224d04b3189ed90c">addEdge</a>, <a href="#a3b13aeab236aa95632c9ef9052c14926">BFI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aae0e48b4d74e4dbcd777495cd16ae822">Lookup</a>.</p>


<p>Referenced by <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

### addNode() {#ad98ee11535062e1034345efac121ec05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::bfi_detail::IrreducibleGraph::addNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a4f2854e822f1b323869fb6c7ae6fc0d0">BlockNode</a> &amp; Node)</td>
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



<p>Definition at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a3b13aeab236aa95632c9ef9052c14926">BFI</a>, <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass/#a42dc56500d44820d4526a0863abc2943">llvm::bfi_detail::BlockMass::getEmpty</a> and <a href="#a8961714adf03d003152f5f785da8b26a">Nodes</a>.</p>


<p>Referenced by <a href="#a0299c4b86be9e4857e810b2160f37cf7">addNodesInFunction</a> and <a href="#add4c9ca63093a8270248e72b08c5302e">addNodesInLoop</a>.</p>

</div>
</div>

### addNodesInFunction() {#a0299c4b86be9e4857e810b2160f37cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IrreducibleGraph::addNodesInFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="#ad98ee11535062e1034345efac121ec05">addNode</a>, <a href="#a3b13aeab236aa95632c9ef9052c14926">BFI</a>, <a href="#a1377985f15180a3717b4a519b13eaedb">indexNodes</a> and <a href="#aac2780a8fb8a885011f9d14494c5c8dc">Start</a>.</p>


<p>Referenced by <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

### addNodesInLoop() {#add4c9ca63093a8270248e72b08c5302e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IrreducibleGraph::addNodesInLoop (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">BFIBase::LoopData</a> &amp; OuterLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="#ad98ee11535062e1034345efac121ec05">addNode</a>, <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata/#a924395e7510f57f986ac032994b20f73">llvm::BlockFrequencyInfoImplBase::LoopData::getHeader</a>, <a href="#a1377985f15180a3717b4a519b13eaedb">indexNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a8961714adf03d003152f5f785da8b26a">Nodes</a>, <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata/#aa694a8c0f8d2a04ac086fc4217615367">llvm::BlockFrequencyInfoImplBase::LoopData::Nodes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#aac2780a8fb8a885011f9d14494c5c8dc">Start</a>.</p>


<p>Referenced by <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

### indexNodes() {#a1377985f15180a3717b4a519b13eaedb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IrreducibleGraph::indexNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>, definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aae0e48b4d74e4dbcd777495cd16ae822">Lookup</a> and <a href="#a8961714adf03d003152f5f785da8b26a">Nodes</a>.</p>


<p>Referenced by <a href="#a0299c4b86be9e4857e810b2160f37cf7">addNodesInFunction</a> and <a href="#add4c9ca63093a8270248e72b08c5302e">addNodesInLoop</a>.</p>

</div>
</div>

### initialize() {#abe3bf5fccbd988d1daf97da30f0b0456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BlockEdgesAdder&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::bfi_detail::IrreducibleGraph::initialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata">BFIBase::LoopData</a> * OuterLoop, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/blockedgesadder">BlockEdgesAdder</a> addBlockEdges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="#a2d4ad30cd1d596501e3d99462d1af74e">addEdges</a>, <a href="#a0299c4b86be9e4857e810b2160f37cf7">addNodesInFunction</a>, <a href="#add4c9ca63093a8270248e72b08c5302e">addNodesInLoop</a>, <a href="#a3b13aeab236aa95632c9ef9052c14926">BFI</a>, <a href="#aae0e48b4d74e4dbcd777495cd16ae822">Lookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/blockfrequencyinfoimplbase/loopdata/#aa694a8c0f8d2a04ac086fc4217615367">llvm::BlockFrequencyInfoImplBase::LoopData::Nodes</a>, <a href="#aac2780a8fb8a885011f9d14494c5c8dc">Start</a> and <a href="#a7b2037773f618188c79aec1444116647">StartIrr</a>.</p>


<p>Referenced by <a href="#a1147f0ef1ac705077e24462022b4ae1e">IrreducibleGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BFI {#a3b13aeab236aa95632c9ef9052c14926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BFIBase&amp; llvm::bfi_detail::IrreducibleGraph::BFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a2d4ad30cd1d596501e3d99462d1af74e">addEdges</a>, <a href="#ad98ee11535062e1034345efac121ec05">addNode</a>, <a href="#a0299c4b86be9e4857e810b2160f37cf7">addNodesInFunction</a>, <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a> and <a href="#a1147f0ef1ac705077e24462022b4ae1e">IrreducibleGraph</a>.</p>

</div>
</div>

### Lookup {#aae0e48b4d74e4dbcd777495cd16ae822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;uint32_t, IrrNode *, 4&gt; llvm::bfi_detail::IrreducibleGraph::Lookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a17262e1cca3f9a69224d04b3189ed90c">addEdge</a>, <a href="#a2d4ad30cd1d596501e3d99462d1af74e">addEdges</a>, <a href="#a1377985f15180a3717b4a519b13eaedb">indexNodes</a> and <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

### Nodes {#a8961714adf03d003152f5f785da8b26a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;IrrNode&gt; llvm::bfi_detail::IrreducibleGraph::Nodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#ad98ee11535062e1034345efac121ec05">addNode</a>, <a href="#add4c9ca63093a8270248e72b08c5302e">addNodesInLoop</a> and <a href="#a1377985f15180a3717b4a519b13eaedb">indexNodes</a>.</p>

</div>
</div>

### Start {#aac2780a8fb8a885011f9d14494c5c8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockNode llvm::bfi_detail::IrreducibleGraph::Start</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#a0299c4b86be9e4857e810b2160f37cf7">addNodesInFunction</a>, <a href="#add4c9ca63093a8270248e72b08c5302e">addNodesInLoop</a> and <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

### StartIrr {#a7b2037773f618188c79aec1444116647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IrrNode* llvm::bfi_detail::IrreducibleGraph::StartIrr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 620 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Referenced by <a href="#abe3bf5fccbd988d1daf97da30f0b0456">initialize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/blockfrequencyinfoimpl-cpp">BlockFrequencyInfoImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
