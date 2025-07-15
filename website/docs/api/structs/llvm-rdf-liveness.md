---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/liveness
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Liveness` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::Liveness { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">llvm/CodeGen/RDFLiveness.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249a71f1e40218410ec7499c4f9bc964">LiveMapType</a> = <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggrmap">RegisterAggrMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2a8f95ee08216cb26351e4f2a7a4447">NodeRef</a> = <a href="/web-llvm/docs/api/namespaces/llvm/rdf/detail/#a7f722f7078d3e80b2821b4a5460b5adf">detail::NodeRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d9efe2288fe64a012fc86b3f188b73d">NodeRefSet</a> = std::unordered_set&lt; <a href="#aa2a8f95ee08216cb26351e4f2a7a4447">NodeRef</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> = std::unordered_map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a>, <a href="#a0d9efe2288fe64a012fc86b3f188b73d">NodeRefSet</a> &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9cd23a5c66dc74c7abbd796884654c">Liveness</a> (MachineRegisterInfo &amp;mri, const DataFlowGraph &amp;g)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad18ad8bc2c127dd4844b3186233d68f5">NodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3a1721c534dbc63fdc081a9365fd9c">getAllReachingDefs</a> (RegisterRef RefRR, NodeAddr&lt; RefNode * &gt; RefA, bool TopShadows, bool FullChain, const RegisterAggr &amp;DefRRs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad18ad8bc2c127dd4844b3186233d68f5">NodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2950ed09c69131f420a4eec16bdd2f83">getAllReachingDefs</a> (NodeAddr&lt; RefNode * &gt; RefA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad18ad8bc2c127dd4844b3186233d68f5">NodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49fbda3592d7a42088a682a5e8b3453">getAllReachingDefs</a> (RegisterRef RefRR, NodeAddr&lt; RefNode * &gt; RefA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af948ed7c1cd7c55a1e8cb255d8742936">getAllReachedUses</a> (RegisterRef RefRR, NodeAddr&lt; DefNode * &gt; DefA, const RegisterAggr &amp;DefRRs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ca653428d94b8f0622950fd1f4879e">getAllReachedUses</a> (RegisterRef RefRR, NodeAddr&lt; DefNode * &gt; DefA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac4e993a140f158582dba7baf107a59e">getAllReachingDefsRec</a> (RegisterRef RefRR, NodeAddr&lt; RefNode * &gt; RefA, NodeSet &amp;Visited, const NodeSet &amp;Defs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186be9b537ac3f4112ac6ea3d610ddf3">getNearestAliasedRef</a> (RegisterRef RefRR, NodeAddr&lt; InstrNode * &gt; IA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the nearest ref node aliased to RefRR, going upwards in the data flow, starting from the instruction immediately preceding Inst. <a href="#a186be9b537ac3f4112ac6ea3d610ddf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a249a71f1e40218410ec7499c4f9bc964">LiveMapType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0adc90650207b3fccdf0c4b9c0a14e32">getLiveMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a249a71f1e40218410ec7499c4f9bc964">LiveMapType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af77d8d402d78d607179aa6ae6d78cb9f">getLiveMap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f55e6f1df33ecbd8db05a5d720f6d3d">getRealUses</a> (NodeId P) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa36c6486058550c0b2c5f347e5f0e48b">computePhiInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac020365416d380fdc2b913c0daf4691b">computeLiveIns</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8700f31ee8c2ff5f803bb291b8fd03">resetLiveIns</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b1afbb10a278d481f7c846a46c36bb9">resetKills</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d444250018e8e065ca05a73bdf3d35">resetKills</a> (MachineBasicBlock *B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc708f1262244491ed2a9eb747454116">trace</a> (bool T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785d9194fc80b4797f23fbdc4ff3d599">getBlockWithRef</a> (NodeId RN) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a763980257cb3570cb373ac2da942ec9f">traverse</a> (MachineBasicBlock *B, RefMap &amp;LiveIn)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ede1dd58a24a2c14725bb7d08c35f8">emptify</a> (RefMap &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc9a2ea1d4d95a1cb7d56df3048e026">getAllReachingDefsRecImpl</a> (RegisterRef RefRR, NodeAddr&lt; RefNode * &gt; RefA, NodeSet &amp;Visited, const NodeSet &amp;Defs, unsigned Nest, unsigned MaxNest)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad35c4a0772292c0ce4d72363ff913446">DFG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef9cfd33ea4923c9fde127c9b69ee73">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo">PhysicalRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbdf1607490092c961463e55d40d4e9">PRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bdb4215e4044bb85515c911df6f8990">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier">MachineDominanceFrontier</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bd1fae3003adcfe623de9ccf475a55c">MDF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a249a71f1e40218410ec7499c4f9bc964">LiveMapType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0960b52253c5891294be0101066e1135">LiveMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1588b7a946f189e449c8d32376c76e36">Empty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76aaa41735e73f435d3e1932459559b">NoRegs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1c8a4843d8204620f9bf4e177eebe7b">Trace</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0890163661a9ec70ef3ac0c618c1e5b5">NBMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a>, <a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c43264498716ad1bdf9d87518d0b88">RealUseMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2627db7e3c9acf2b694b3fe353d11bc4">IIDF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17edda64888cd74cb533b96606789ab8">PhiLON</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24b8b59f8540dc532d307e287857019">PhiLOX</a></td>
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


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LiveMapType {#a249a71f1e40218410ec7499c4f9bc964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::Liveness::LiveMapType =  RegisterAggrMap&lt;MachineBasicBlock *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### NodeRef {#aa2a8f95ee08216cb26351e4f2a7a4447}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::Liveness::NodeRef =  detail::NodeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### NodeRefSet {#a0d9efe2288fe64a012fc86b3f188b73d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::Liveness::NodeRefSet =  std::unordered_set&lt;NodeRef&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### RefMap {#ae0aea4a799ad5f9d4015066269451fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::Liveness::RefMap =  std::unordered_map&lt;RegisterId, NodeRefSet&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Liveness() {#a4b9cd23a5c66dc74c7abbd796884654c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::Liveness::Liveness (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; mri, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; g)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-portable-c/#ab5958fad499ed692422c66bb20000a39">g</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### computeLiveIns() {#ac020365416d380fdc2b913c0daf4691b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::computeLiveIns ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ad0bf95396cec46a41371341460d14a1c">llvm::SetVector&lt; T, Vector, Set, N &gt;::begin</a>, <a href="#aa36c6486058550c0b2c5f347e5f0e48b">computePhiInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a889cc0df630d4b01e12d359517e26670">llvm::SetVector&lt; T, Vector, Set, N &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="#a0c3a1721c534dbc63fdc081a9365fd9c">getAllReachingDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da0ae60988901d9b6e0499d07f94e8fc00">llvm::rdf::NodeAttrs::Phi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a51d767cf7aced5470bd37a0ff02545a7">llvm::rdf::Print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121daf9dd39c923393e08fbf871e15cc530b2">llvm::rdf::NodeAttrs::Use</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#acb675de67baa3aed372fdf62b440c866">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### computePhiInfo() {#aa36c6486058550c0b2c5f347e5f0e48b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::computePhiInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a5e4c4c57dcce871494c8ac465bcb0edb">llvm::rdf::RegisterAggr::clearIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da71d294f05b9e9fa97d22c44e016bbbf9">llvm::rdf::NodeAttrs::Dead</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121dacde70c4b68233671ba64c60b7ec08238">llvm::rdf::NodeAttrs::Def</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a0c3a1721c534dbc63fdc081a9365fd9c">getAllReachingDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aa51570c2c0b445c77a89a0018b0670f7">llvm::rdf::RegisterAggr::hasAliasOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aad8037343d867187c11d52da840d72f6">llvm::rdf::RegisterAggr::intersectWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a979659ec464cee64a84df219494fc2ea">IsDead</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da0ae60988901d9b6e0499d07f94e8fc00">llvm::rdf::NodeAttrs::Phi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">llvm::rdf::NodeAttrs::PhiRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a51d767cf7aced5470bd37a0ff02545a7">llvm::rdf::Print</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da19efcb0576040c1305e80dcc42758551">llvm::rdf::NodeAttrs::Undef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121daf9dd39c923393e08fbf871e15cc530b2">llvm::rdf::NodeAttrs::Use</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#ac020365416d380fdc2b913c0daf4691b">computeLiveIns</a>.</p>

</div>
</div>

### getAllReachedUses() {#af948ed7c1cd7c55a1e8cb255d8742936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeSet llvm::rdf::Liveness::getAllReachedUses (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode">DefNode</a> * &gt; DefA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; DefRRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 414 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da71d294f05b9e9fa97d22c44e016bbbf9">llvm::rdf::NodeAttrs::Dead</a>, <a href="#af948ed7c1cd7c55a1e8cb255d8742936">getAllReachedUses</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode/#a37650e1cbcdcbae779a3b0b09367d067">llvm::rdf::RefNode::getSibling</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a979659ec464cee64a84df219494fc2ea">IsDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da19efcb0576040c1305e80dcc42758551">llvm::rdf::NodeAttrs::Undef</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeloadsintofakeuses-cpp/#a0b427ca665b192edbeb8d6ca3c8f19fd">Uses</a>.</p>


<p>Referenced by <a href="#ab9ca653428d94b8f0622950fd1f4879e">getAllReachedUses</a> and <a href="#af948ed7c1cd7c55a1e8cb255d8742936">getAllReachedUses</a>.</p>

</div>
</div>

### getAllReachedUses() {#ab9ca653428d94b8f0622950fd1f4879e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeSet llvm::rdf::Liveness::getAllReachedUses (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/defnode">DefNode</a> * &gt; DefA)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<p>Reference <a href="#af948ed7c1cd7c55a1e8cb255d8742936">getAllReachedUses</a>.</p>

</div>
</div>

### getAllReachingDefs() {#a0c3a1721c534dbc63fdc081a9365fd9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::rdf::Liveness::getAllReachingDefs (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a> * &gt; RefA, bool TopShadows, bool FullChain, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp; DefRRs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da71d294f05b9e9fa97d22c44e016bbbf9">llvm::rdf::NodeAttrs::Dead</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121dacde70c4b68233671ba64c60b7ec08238">llvm::rdf::NodeAttrs::Def</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a7de5a04920954ac964059cfc428ad">llvm::erase_if</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#abe99acebac6f58f70d09de84f5becbdf">llvm::rdf::RegisterAggr::hasCoverOf</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a23019059b3e22c404f87ee4fd36f7fae">llvm::rdf::RegisterAggr::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#aebb69ff57b201dee748ce7fe7f22ff1b">llvm::rdf::RegisterAggr::isCoverOf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da0ae60988901d9b6e0499d07f94e8fc00">llvm::rdf::NodeAttrs::Phi</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">llvm::rdf::NodeAttrs::PhiRef</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da64fd1d9beb2a27391a05ee1d6d51b6e0">llvm::rdf::NodeAttrs::Preserving</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a1a42c1ba878bd637f374197d05f0a97f">llvm::SetVector&lt; T, Vector, Set, N &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da91376b865b14d172148590ff1c69e403">llvm::rdf::NodeAttrs::Stmt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da19efcb0576040c1305e80dcc42758551">llvm::rdf::NodeAttrs::Undef</a>.</p>


<p>Referenced by <a href="#ac020365416d380fdc2b913c0daf4691b">computeLiveIns</a>, <a href="#aa36c6486058550c0b2c5f347e5f0e48b">computePhiInfo</a>, <a href="#a2950ed09c69131f420a4eec16bdd2f83">getAllReachingDefs</a> and <a href="#aa49fbda3592d7a42088a682a5e8b3453">getAllReachingDefs</a>.</p>

</div>
</div>

### getAllReachingDefs() {#a2950ed09c69131f420a4eec16bdd2f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::rdf::Liveness::getAllReachingDefs (<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a> * &gt; RefA)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a> and <a href="#a0c3a1721c534dbc63fdc081a9365fd9c">getAllReachingDefs</a>.</p>

</div>
</div>

### getAllReachingDefs() {#aa49fbda3592d7a42088a682a5e8b3453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::rdf::Liveness::getAllReachingDefs (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a> * &gt; RefA)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<p>Reference <a href="#a0c3a1721c534dbc63fdc081a9365fd9c">getAllReachingDefs</a>.</p>

</div>
</div>

### getAllReachingDefsRec() {#aac4e993a140f158582dba7baf107a59e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; NodeSet, bool &gt; llvm::rdf::Liveness::getAllReachingDefsRec (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a> * &gt; RefA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a> &amp; Visited, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a> &amp; Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp/#a9d96a5052466b04ba46179d0a0bb3420">MaxRecNest</a>.</p>

</div>
</div>

### getLiveMap() {#a0adc90650207b3fccdf0c4b9c0a14e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveMapType &amp; llvm::rdf::Liveness::getLiveMap ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### getLiveMap() {#af77d8d402d78d607179aa6ae6d78cb9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveMapType &amp; llvm::rdf::Liveness::getLiveMap ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### getNearestAliasedRef() {#a186be9b537ac3f4112ac6ea3d610ddf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeAddr&lt; RefNode * &gt; llvm::rdf::Liveness::getNearestAliasedRef (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/instrnode">InstrNode</a> * &gt; IA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the nearest ref node aliased to RefRR, going upwards in the data flow, starting from the instruction immediately preceding Inst.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121daccc816e76d83a88e73d024590c88260f">llvm::rdf::NodeAttrs::Clobbering</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a7e398d2285d22a33c3358ed7904725d7">llvm::rdf::NodeAddr&lt; T &gt;::Id</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getRealUses() {#a0f55e6f1df33ecbd8db05a5d720f6d3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RefMap &amp; llvm::rdf::Liveness::getRealUses (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> P)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### resetKills() {#a6b1afbb10a278d481f7c846a46c36bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::resetKills ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 910 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a6b1afbb10a278d481f7c846a46c36bb9">resetKills</a>.</p>


<p>Referenced by <a href="#a6b1afbb10a278d481f7c846a46c36bb9">resetKills</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#acb675de67baa3aed372fdf62b440c866">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### resetKills() {#aa4d444250018e8e065ca05a73bdf3d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::resetKills (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator/#af858f1c705b821986610cb81dcda2245">llvm::MCSubRegIndexIterator::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator/#ac6da77ae7e55006bcd05c1c288235d13">llvm::MCSubRegIndexIterator::getSubRegIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsubregindexiterator/#a4bc33f765fada85ad09c4910d122832d">llvm::MCSubRegIndexIterator::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a168122d6ac4ed2a8b722e01b592ad289">llvm::BitVector::reset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>.</p>

</div>
</div>

### resetLiveIns() {#a6c8700f31ee8c2ff5f803bb291b8fd03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::resetLiveIns ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a1506ec20a7c8917bd3ba56eaf56916e7">llvm::rdf::RegisterAggr::refs</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#acb675de67baa3aed372fdf62b440c866">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::runOnMachineFunction</a>.</p>

</div>
</div>

### trace() {#acc708f1262244491ed2a9eb747454116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::trace (bool T)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonrdfopt-cpp-/hexagonrdfopt/#acb675de67baa3aed372fdf62b440c866">anonymous{HexagonRDFOpt.cpp}::HexagonRDFOpt::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### emptify() {#ad9ede1dd58a24a2c14725bb7d08c35f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::emptify (<a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>

</div>
</div>

### getAllReachingDefsRecImpl() {#aefc9a2ea1d4d95a1cb7d56df3048e026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; NodeSet, bool &gt; llvm::rdf::Liveness::getAllReachingDefsRecImpl (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RefRR, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/refnode">RefNode</a> * &gt; RefA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a> &amp; Visited, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad11f45edf83605cb43ad18e1802fe8bc">NodeSet</a> &amp; Defs, unsigned Nest, unsigned MaxNest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>

</div>
</div>

### getBlockWithRef() {#a785d9194fc80b4797f23fbdc4ff3d599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::rdf::Liveness::getBlockWithRef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> RN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>

</div>
</div>

### traverse() {#a763980257cb3570cb373ac2da942ec9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::Liveness::traverse (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * B, <a href="#ae0aea4a799ad5f9d4015066269451fb1">RefMap</a> &amp; LiveIn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>, definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DFG {#ad35c4a0772292c0ce4d72363ff913446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataFlowGraph&amp; llvm::rdf::Liveness::DFG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### Empty {#a1588b7a946f189e449c8d32376c76e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RefMap llvm::rdf::Liveness::Empty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### IIDF {#a2627db7e3c9acf2b694b3fe353d11bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MachineBasicBlock *, std::set&lt;MachineBasicBlock *&gt; &gt; llvm::rdf::Liveness::IIDF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### LiveMap {#a0960b52253c5891294be0101066e1135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveMapType llvm::rdf::Liveness::LiveMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### MDF {#a9bd1fae3003adcfe623de9ccf475a55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominanceFrontier&amp; llvm::rdf::Liveness::MDF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### MDT {#a9bdb4215e4044bb85515c911df6f8990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominatorTree&amp; llvm::rdf::Liveness::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### NBMap {#a0890163661a9ec70ef3ac0c618c1e5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;NodeId, MachineBasicBlock *&gt; llvm::rdf::Liveness::NBMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### NoRegs {#ad76aaa41735e73f435d3e1932459559b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterAggr llvm::rdf::Liveness::NoRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### PhiLON {#a17edda64888cd74cb533b96606789ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MachineBasicBlock *, RefMap&gt; llvm::rdf::Liveness::PhiLON</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### PhiLOX {#ab24b8b59f8540dc532d307e287857019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MachineBasicBlock *, RefMap&gt; llvm::rdf::Liveness::PhiLOX</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### PRI {#a8bbdf1607490092c961463e55d40d4e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PhysicalRegisterInfo&amp; llvm::rdf::Liveness::PRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### RealUseMap {#a74c43264498716ad1bdf9d87518d0b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;NodeId, RefMap&gt; llvm::rdf::Liveness::RealUseMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### Trace {#ac1c8a4843d8204620f9bf4e177eebe7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::Liveness::Trace = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

### TRI {#a6ef9cfd33ea4923c9fde127c9b69ee73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::rdf::Liveness::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfliveness-h">RDFLiveness.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfliveness-cpp">RDFLiveness.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
