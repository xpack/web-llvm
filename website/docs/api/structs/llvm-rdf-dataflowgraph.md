---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/dataflowgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DataFlowGraph` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::DataFlowGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> = std::unordered_map&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac7072dcf10008631e0ac026bc5f8beae">RegisterId</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/defstack">DefStack</a> &gt;</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70da8ad930312fdf8d627a78bacc4fec">BlockRefsMap</a> = <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggrmap">RegisterAggrMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38fd70c7cf138c96283ce7c265a85b0e">DataFlowGraph</a> (MachineFunction &amp;mf, const TargetInstrInfo &amp;tii, const TargetRegisterInfo &amp;tri, const MachineDominatorTree &amp;mdt, const MachineDominanceFrontier &amp;mdf)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef633ea27194c84482f39fb514608153">DataFlowGraph</a> (MachineFunction &amp;mf, const TargetInstrInfo &amp;tii, const TargetRegisterInfo &amp;tri, const MachineDominatorTree &amp;mdt, const MachineDominanceFrontier &amp;mdf, const TargetOperandInfo &amp;toi)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase">NodeBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad913e83d1b4439ce665f911348d7d616">ptr</a> (NodeId N) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ee71e8d993c1deb028f6299d055340f">ptr</a> (NodeId N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03dbe5b66a2fcf387596fc6b3c3fc33a">id</a> (const NodeBase *P) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff0e0649aacc0cb7884acdb2caf3888c">addr</a> (NodeId N) const -&gt; <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; T &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad43aeb5ac76bcef25986fbb0918d1165">Func</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5562ece880571d0c026d45af0a4bf7dc">getFunc</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772157ecd8233578fc88b4c03e5a84a3">getMF</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a821459d25ce1155f29f2cb3a94b1d016">getTII</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd2f7d7ac1d171df6efaabdc99e3a9bd">getTRI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abec99855593657b93d529312c2d3885a">getPRI</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb00ab66e3522120ac68c0a3f2aba5e">getDT</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a64e4409d7fce1aa0df5b9685d1d735">getDF</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075bd3b473f35178716fa6804a580289">getLiveIns</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b52d2ebf631ded594b7311d1f2829e3">build</a> (const Config &amp;config)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa816492d5310d33ee910f0808244e65">build</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd79669de85357a98f3c352ba9209263">pushAllDefs</a> (Instr IA, DefStackMap &amp;DM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad07faf4d1852a9a99b32a798edf6170d">markBlock</a> (NodeId B, DefStackMap &amp;DefM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b818af3f643e001a63611d86f2776c8">releaseBlock</a> (NodeId B, DefStackMap &amp;DefM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/packedregisterref">PackedRegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cef8f9dc36d8b31cbca1f5f9aa9d443">pack</a> (RegisterRef RR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/packedregisterref">PackedRegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b19879536810b447231e0efab10a5e">pack</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21825ee3c5ced2b0878c0757333703e7">unpack</a> (PackedRegisterRef PR) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae2387cb76daa6d4328c2cc9ab5e850">makeRegRef</a> (unsigned Reg, unsigned Sub) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db43a426340879bc67cffe68aa63c12">makeRegRef</a> (const MachineOperand &amp;Op) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf45c81b2f8aaa8a8968e5e0a6cd68e">getNextRelated</a> (Instr IA, Ref RA) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f334bed0e58d5470180436d28993035">getNextShadow</a> (Instr IA, Ref RA, bool Create)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7010e9f697823cc5a40876345bab137e">getRelatedRefs</a> (Instr IA, Ref RA) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb81b82d10d84e8dfd99c1e206f72766">findBlock</a> (MachineBasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06996b487189a734a367e0f1d101ed78">unlinkUse</a> (Use UA, bool RemoveFromOwner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a707e4fe8684ad000cde8d9c302d0eca1">unlinkDef</a> (Def DA, bool RemoveFromOwner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a41a96168b65e3d82f095f46ee9d9d6">isTracked</a> (RegisterRef RR) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d37a7eb6fa39a78f3bcb706766bd73">hasUntrackedRef</a> (Stmt S, bool IgnoreReserved=true) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6adad77c49bee969463a5fccb4f6cd2d">reset</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a39561fe4b1bfb6f59ce103a11a8206">getLandingPadLiveIns</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30db3e8a739ddfa562852c963c121b45">newNode</a> (uint16_t Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f29717fdef8fd2bf1bc0ec714faeef1">cloneNode</a> (const Node B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#abd774f5d3a81e00ffb690f4f5c0c82cf">Use</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a9894669fa66794cd30f244061a4fd">newUse</a> (Instr Owner, MachineOperand &amp;Op, uint16_t Flags=NodeAttrs::None)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a61dda01f89004e5cfed5414e881d1af3">PhiUse</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac896a715108cd6feea3c72c553c4369a">newPhiUse</a> (Phi Owner, RegisterRef RR, Block PredB, uint16_t Flags=NodeAttrs::PhiRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a10793004faece2bb74d3363b5f6ce96f">Def</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5620d15236f6bd3ed6052c5557c98849">newDef</a> (Instr Owner, MachineOperand &amp;Op, uint16_t Flags=NodeAttrs::None)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a10793004faece2bb74d3363b5f6ce96f">Def</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d02984e29158fb04e2404a416543a63">newDef</a> (Instr Owner, RegisterRef RR, uint16_t Flags=NodeAttrs::PhiRef)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a379bee2dadbfd1d7a599f003c4275dd8">Phi</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a15f10ed67c8e5deb855627ad29b5e2">newPhi</a> (Block Owner)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a8c7e161293378ff6f6f82fc3c167870c">Stmt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70a8ca2a626fdf7ad0e38e94d7071dc3">newStmt</a> (Block Owner, MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08bb7461bdc1960c948a3486df776b41">newBlock</a> (Func Owner, MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad43aeb5ac76bcef25986fbb0918d1165">Func</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732da27bd5b65b4cbb56f213fbed976e">newFunc</a> (MachineFunction *MF)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6f6756051edd4be23b92b43ba7cce021">locateNextRef</a> (Instr IA, Ref RA, Predicate P) const -&gt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125776262a2b041e990dfd1cbab87df5">buildStmt</a> (Block BA, MachineInstr &amp;In)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c4dabe1a820445461262732fb9abdc5">recordDefsForDF</a> (BlockRefsMap &amp;PhiM, Block BA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b1c5d90376e1b638ac1a2eacb74fbe">buildPhis</a> (BlockRefsMap &amp;PhiM, Block BA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d2646041a1c1f7e05ea220e2b79dcf">removeUnusedPhis</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7927bb0563f7b259b240139af1a076">pushClobbers</a> (Instr IA, DefStackMap &amp;DM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8013ce532a1a42ba6c4f55f058d89cb">pushDefs</a> (Instr IA, DefStackMap &amp;DM)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a35a6167085e3d68b677601e25985d72f">linkRefUp</a> (Instr IA, NodeAddr&lt; T &gt; TA, DefStack &amp;DS)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Predicate&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16cad01b04fee48457464d19bb98a4a8">linkStmtRefs</a> (DefStackMap &amp;DefM, Stmt SA, Predicate P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845c59031ff947857332a5a11330c615">linkBlockRefs</a> (DefStackMap &amp;DefM, Block BA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8055d9ece9d0b6729d20b9c88b2c514">unlinkUseDF</a> (Use UA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e26d6a179743154dd2920e3b131dcf8">unlinkDefDF</a> (Def DA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a963bcbca3fecd1f5a2a4dea246e00b0f">removeFromOwner</a> (Ref RA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/rdf/targetoperandinfo">TargetOperandInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bac24a2593cf0ba78aba1b5ce16d05b">DefaultTOI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32746e872d0c4bc7b0a30ce043b595ca">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91ab379c5bf86a25604cfe80b9583d2">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684f3b76c26e54ea488075fe62fbde8b">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo">PhysicalRegisterInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21d97b52b5758dbe183280724a7d835a">PRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcfe9d846ae55ff085e9b272bdbfceb5">MDT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2231c864afea6eec7591b6ee3b993b29">MDF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/targetoperandinfo">TargetOperandInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56445a91ab0003593c22786f8360e8c8">TOI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr">RegisterAggr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc20b0f238313f1ea24a0fec84d16d66">LiveIns</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad43aeb5ac76bcef25986fbb0918d1165">Func</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef11930e159344e7a209835fe093b78d">TheFunc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/nodeallocator">NodeAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6df7d0610a945ab8663b5e6e2ad84d2">Memory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec227602630191edc1e368d312ea0ef">BlockNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/lanemaskindex">LaneMaskIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304334326dc4a33b8ebb66dc5080c610">LMI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/config">Config</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c30e38d2e4d603a821bd0467dc0caa">BuildCfg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::set&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d692986a02d693615e109d32db75c85">TrackedUnits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8149a6e14d4f0fc0b8da64f2272152e">ReservedRegs</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;uint16_t Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a924c78446e6a6bca9371f02ae6c62b7b">IsRef</a> (const Node BA)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;uint16_t Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8b5aa2c1dd5ee4a4a8bf03730965c29">IsCode</a> (const Node BA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264db9e61fcbc7db438de1f6a062a96a">IsDef</a> (const Node BA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a057fa5769de2acccd16b02326468b3">IsUse</a> (const Node BA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555e904e68d3d41e5f2db6beaabd49a9">IsPhi</a> (const Node BA)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67533efd5231172ec9eb37c4ff10aec1">IsPreservingDef</a> (const Def DA)</td>
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


<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DefStackMap {#af9ba4adb1171c03b53e7c67ab59825ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::DataFlowGraph::DefStackMap =  std::unordered_map&lt;RegisterId, DefStack&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### BlockRefsMap {#a70da8ad930312fdf8d627a78bacc4fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::rdf::DataFlowGraph::BlockRefsMap =  RegisterAggrMap&lt;NodeId&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DataFlowGraph() {#a38fd70c7cf138c96283ce7c265a85b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::DataFlowGraph::DataFlowGraph (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; tii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; tri, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp; mdt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier">MachineDominanceFrontier</a> &amp; mdf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### DataFlowGraph() {#aef633ea27194c84482f39fb514608153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::rdf::DataFlowGraph::DataFlowGraph (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; tii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; tri, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp; mdt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinedominancefrontier">MachineDominanceFrontier</a> &amp; mdf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/targetoperandinfo">TargetOperandInfo</a> &amp; toi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 644 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addr() {#aff0e0649aacc0cb7884acdb2caf3888c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeAddr&lt; T &gt; llvm::rdf::DataFlowGraph::addr (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> N)</td>
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



<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ad913e83d1b4439ce665f911348d7d616">ptr</a>.</p>

</div>
</div>

### build() {#a0b52d2ebf631ded594b7311d1f2829e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::build (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/config">Config</a> &amp; config)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a5afff33fe198a8b00e021bf562a82dcb">llvm::rdf::CodeNode::addMember</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a8550509e5a44adcccec5d4c23b1536ec">llvm::rdf::RegisterAggr::empty</a>, <a href="#adb81b82d10d84e8dfd99c1e206f72766">findBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#ac31264a23924e7566514128d8b64b9a9">llvm::rdf::BlockNode::getCode</a>, <a href="#abec99855593657b93d529312c2d3885a">getPRI</a>, <a href="#afd2f7d7ac1d171df6efaabdc99e3a9bd">getTRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a1a41a96168b65e3d82f095f46ee9d9d6">isTracked</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/buildoptions/#ae7c99d4ee46b611ce85b07006be760e5ae2a5bd0f0e3442f62c978d02d2ec5482">llvm::rdf::BuildOptions::KeepDeadPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a364ed6e68f92f797c0cd9e53ce5ea2a5">llvm::MachineBasicBlock::liveins</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/buildoptions/#ae7c99d4ee46b611ce85b07006be760e5ab0366004added4b326831758a469cb96">llvm::rdf::BuildOptions::OmitReserved</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">llvm::rdf::NodeAttrs::PhiRef</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a877507fda31c207ec36a018784369708">llvm::MachineBasicBlock::pred_empty</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da64fd1d9beb2a27391a05ee1d6d51b6e0">llvm::rdf::NodeAttrs::Preserving</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggr/#a1506ec20a7c8917bd3ba56eaf56916e7">llvm::rdf::RegisterAggr::refs</a>.</p>

</div>
</div>

### build() {#afa816492d5310d33ee910f0808244e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::build ()</td>
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



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Reference <a href="#afa816492d5310d33ee910f0808244e65">build</a>.</p>


<p>Referenced by <a href="#afa816492d5310d33ee910f0808244e65">build</a>.</p>

</div>
</div>

### findBlock() {#adb81b82d10d84e8dfd99c1e206f72766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block llvm::rdf::DataFlowGraph::findBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="#a0b52d2ebf631ded594b7311d1f2829e3">build</a>.</p>

</div>
</div>

### getDF() {#a5a64e4409d7fce1aa0df5b9685d1d735}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominanceFrontier &amp; llvm::rdf::DataFlowGraph::getDF ()</td>
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



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### getDT() {#a6fb00ab66e3522120ac68c0a3f2aba5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominatorTree &amp; llvm::rdf::DataFlowGraph::getDT ()</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### getFunc() {#a5562ece880571d0c026d45af0a4bf7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Func llvm::rdf::DataFlowGraph::getFunc ()</td>
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



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### getLiveIns() {#a075bd3b473f35178716fa6804a580289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterAggr &amp; llvm::rdf::DataFlowGraph::getLiveIns ()</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### getMF() {#a772157ecd8233578fc88b4c03e5a84a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction &amp; llvm::rdf::DataFlowGraph::getMF ()</td>
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



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### getNextRelated() {#a0cf45c81b2f8aaa8a8968e5e0a6cd68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ref llvm::rdf::DataFlowGraph::getNextRelated (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a> RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/phiusenode/#a61edd9a1eb4a1bfc93bf58ad5073b872">llvm::rdf::PhiUseNode::getPredecessor</a>, <a href="#abec99855593657b93d529312c2d3885a">getPRI</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da0ae60988901d9b6e0499d07f94e8fc00">llvm::rdf::NodeAttrs::Phi</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da91376b865b14d172148590ff1c69e403">llvm::rdf::NodeAttrs::Stmt</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121daf9dd39c923393e08fbf871e15cc530b2">llvm::rdf::NodeAttrs::Use</a>.</p>


<p>Referenced by <a href="#a7010e9f697823cc5a40876345bab137e">getRelatedRefs</a>.</p>

</div>
</div>

### getNextShadow() {#a4f334bed0e58d5470180436d28993035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ref llvm::rdf::DataFlowGraph::getNextShadow (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a> RA, bool Create)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a0c6eec2ca178b22b6d5c09ffcc021e88">llvm::rdf::NodeBase::setFlags</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da6ffc2b2c02cab44f33a91b48bd374461">llvm::rdf::NodeAttrs::Shadow</a>.</p>

</div>
</div>

### getPRI() {#abec99855593657b93d529312c2d3885a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PhysicalRegisterInfo &amp; llvm::rdf::DataFlowGraph::getPRI ()</td>
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



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="#a0b52d2ebf631ded594b7311d1f2829e3">build</a>, <a href="#a0cf45c81b2f8aaa8a8968e5e0a6cd68e">getNextRelated</a>, <a href="#a1a41a96168b65e3d82f095f46ee9d9d6">isTracked</a> and <a href="#a2db43a426340879bc67cffe68aa63c12">makeRegRef</a>.</p>

</div>
</div>

### getRelatedRefs() {#a7010e9f697823cc5a40876345bab137e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeList llvm::rdf::DataFlowGraph::getRelatedRefs (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a> RA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0cf45c81b2f8aaa8a8968e5e0a6cd68e">getNextRelated</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sioptimizeexecmaskingprera-cpp/#a3e47bdb3e296b00df96eff7896fa57bf">RA</a>.</p>

</div>
</div>

### getTII() {#a821459d25ce1155f29f2cb3a94b1d016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo &amp; llvm::rdf::DataFlowGraph::getTII ()</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### getTRI() {#afd2f7d7ac1d171df6efaabdc99e3a9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo &amp; llvm::rdf::DataFlowGraph::getTRI ()</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Referenced by <a href="#a0b52d2ebf631ded594b7311d1f2829e3">build</a>.</p>

</div>
</div>

### hasUntrackedRef() {#ae0d37a7eb6fa39a78f3bcb706766bd73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::hasUntrackedRef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a8c7e161293378ff6f6f82fc3c167870c">Stmt</a> S, bool IgnoreReserved=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/stmtnode/#ae16b26d08408d8aec231bbe13bc9e9f9">llvm::rdf::StmtNode::getCode</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a05a3bdf2a3d5c33f370bc778fabaee9c">llvm::rdf::RegisterRef::idx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a6e855d6b2f844f3bdce575f3d0330bb5">llvm::rdf::RegisterRef::isReg</a>, <a href="#a1a41a96168b65e3d82f095f46ee9d9d6">isTracked</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a59ca51e5707323e7ed6f1fa512b3f589">llvm::rdf::CodeNode::members</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>.</p>

</div>
</div>

### id() {#a03dbe5b66a2fcf387596fc6b3c3fc33a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeId llvm::rdf::DataFlowGraph::id (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase">NodeBase</a> * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### isTracked() {#a1a41a96168b65e3d82f095f46ee9d9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::isTracked (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ae3b5e436afeb0d1e4781f4c47beee60d">llvm::rdf::disjoint</a> and <a href="#abec99855593657b93d529312c2d3885a">getPRI</a>.</p>


<p>Referenced by <a href="#a0b52d2ebf631ded594b7311d1f2829e3">build</a> and <a href="#ae0d37a7eb6fa39a78f3bcb706766bd73">hasUntrackedRef</a>.</p>

</div>
</div>

### makeRegRef() {#a1ae2387cb76daa6d4328c2cc9ab5e850}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::DataFlowGraph::makeRegRef (unsigned Reg, unsigned Sub)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a7a6e00a1aed89e42fd185379d3309666">llvm::rdf::RegisterRef::isMaskId</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a987ae88dea5396b51031fe9a52d8388a">llvm::rdf::RegisterRef::isRegId</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a2db43a426340879bc67cffe68aa63c12">makeRegRef</a>.</p>

</div>
</div>

### makeRegRef() {#a2db43a426340879bc67cffe68aa63c12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::DataFlowGraph::makeRegRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="#abec99855593657b93d529312c2d3885a">getPRI</a> and <a href="#a1ae2387cb76daa6d4328c2cc9ab5e850">makeRegRef</a>.</p>

</div>
</div>

### markBlock() {#ad07faf4d1852a9a99b32a798edf6170d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::markBlock (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> B, <a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DefM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1001 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### pack() {#a0cef8f9dc36d8b31cbca1f5f9aa9d443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedRegisterRef llvm::rdf::DataFlowGraph::pack (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a>.</p>

</div>
</div>

### pack() {#a96b19879536810b447231e0efab10a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PackedRegisterRef llvm::rdf::DataFlowGraph::pack (<a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR)</td>
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



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#a5ad5cb9affeee19ca5894e5d950ea869">llvm::rdf::RegisterRef::Mask</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref/#aff344ef4b411a5f449ef8839d98f1750">llvm::rdf::RegisterRef::Reg</a>.</p>

</div>
</div>

### ptr() {#ad913e83d1b4439ce665f911348d7d616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeBase * llvm::rdf::DataFlowGraph::ptr (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#aff0e0649aacc0cb7884acdb2caf3888c">addr</a> and <a href="#a9ee71e8d993c1deb028f6299d055340f">ptr</a>.</p>

</div>
</div>

### ptr() {#a9ee71e8d993c1deb028f6299d055340f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::rdf::DataFlowGraph::ptr (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> N)</td>
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



<p>Definition at line 683 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#ad913e83d1b4439ce665f911348d7d616">ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### pushAllDefs() {#afd79669de85357a98f3c352ba9209263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::pushAllDefs (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1026 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### releaseBlock() {#a0b818af3f643e001a63611d86f2776c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::releaseBlock (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a9c5c1abf54c7f5aaf8add770214aba5d">NodeId</a> B, <a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DefM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1008 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### unlinkDef() {#a707e4fe8684ad000cde8d9c302d0eca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::unlinkDef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a10793004faece2bb74d3363b5f6ce96f">Def</a> DA, bool RemoveFromOwner)</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### unlinkUse() {#a06996b487189a734a367e0f1d101ed78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::unlinkUse (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#abd774f5d3a81e00ffb690f4f5c0c82cf">Use</a> UA, bool RemoveFromOwner)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### unpack() {#a21825ee3c5ced2b0878c0757333703e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterRef llvm::rdf::DataFlowGraph::unpack (<a href="/web-llvm/docs/api/structs/llvm/rdf/packedregisterref">PackedRegisterRef</a> PR)</td>
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



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/packedregisterref/#a151d75db72311be1e5a0f94879adfa1b">llvm::rdf::PackedRegisterRef::MaskId</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/packedregisterref/#a1df78b78f3fb694804ad7472ea9a5226">llvm::rdf::PackedRegisterRef::Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildPhis() {#a49b1c5d90376e1b638ac1a2eacb74fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::buildPhis (<a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggrmap">BlockRefsMap</a> &amp; PhiM, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> BA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1424 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### buildStmt() {#a125776262a2b041e990dfd1cbab87df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::buildStmt (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> BA, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; In)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### cloneNode() {#a8f29717fdef8fd2bf1bc0ec714faeef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node llvm::rdf::DataFlowGraph::cloneNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 783 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### getLandingPadLiveIns() {#a2a39561fe4b1bfb6f59ce103a11a8206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr llvm::rdf::DataFlowGraph::getLandingPadLiveIns ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 848 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### linkBlockRefs() {#a845c59031ff947857332a5a11330c615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::linkBlockRefs (<a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DefM, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> BA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1579 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### linkRefUp() {#a35a6167085e3d68b677601e25985d72f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::linkRefUp (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr">NodeAddr</a>&lt; T &gt; TA, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/defstack">DefStack</a> &amp; DS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1506 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### linkStmtRefs() {#a16cad01b04fee48457464d19bb98a4a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::linkStmtRefs (<a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DefM, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a8c7e161293378ff6f6f82fc3c167870c">Stmt</a> SA, <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1548 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### locateNextRef() {#a6f6756051edd4be23b92b43ba7cce021}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Predicate&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Ref, Ref &gt; llvm::rdf::DataFlowGraph::locateNextRef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a> RA, <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newBlock() {#a08bb7461bdc1960c948a3486df776b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block llvm::rdf::DataFlowGraph::newBlock (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad43aeb5ac76bcef25986fbb0918d1165">Func</a> Owner, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newDef() {#a5620d15236f6bd3ed6052c5557c98849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Def llvm::rdf::DataFlowGraph::newDef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> Owner, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, uint16_t Flags=<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121dafbb338819a49cc97e98aaba2a6cd258b">NodeAttrs::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 817 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newDef() {#a6d02984e29158fb04e2404a416543a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Def llvm::rdf::DataFlowGraph::newDef (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> Owner, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR, uint16_t Flags=<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">NodeAttrs::PhiRef</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 823 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newFunc() {#a732da27bd5b65b4cbb56f213fbed976e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Func llvm::rdf::DataFlowGraph::newFunc (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newNode() {#a30db3e8a739ddfa562852c963c121b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node llvm::rdf::DataFlowGraph::newNode (uint16_t Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 774 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newPhi() {#a9a15f10ed67c8e5deb855627ad29b5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Phi llvm::rdf::DataFlowGraph::newPhi (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> Owner)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newPhiUse() {#ac896a715108cd6feea3c72c553c4369a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PhiUse llvm::rdf::DataFlowGraph::newPhiUse (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a379bee2dadbfd1d7a599f003c4275dd8">Phi</a> Owner, <a href="/web-llvm/docs/api/structs/llvm/rdf/registerref">RegisterRef</a> RR, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> PredB, uint16_t Flags=<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1ec381406c0c91aef4a414bdba131112">NodeAttrs::PhiRef</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 808 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newStmt() {#a70a8ca2a626fdf7ad0e38e94d7071dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Stmt llvm::rdf::DataFlowGraph::newStmt (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> Owner, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### newUse() {#a82a9894669fa66794cd30f244061a4fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use llvm::rdf::DataFlowGraph::newUse (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> Owner, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op, uint16_t Flags=<a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121dafbb338819a49cc97e98aaba2a6cd258b">NodeAttrs::None</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### pushClobbers() {#a1c7927bb0563f7b259b240139af1a076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::pushClobbers (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1033 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### pushDefs() {#aa8013ce532a1a42ba6c4f55f058d89cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::pushDefs (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a173a2217e059f21fb25908fa2bf796d6">Instr</a> IA, <a href="#af9ba4adb1171c03b53e7c67ab59825ab">DefStackMap</a> &amp; DM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### recordDefsForDF() {#a3c4dabe1a820445461262732fb9abdc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::recordDefsForDF (<a href="/web-llvm/docs/api/structs/llvm/rdf/registeraggrmap">BlockRefsMap</a> &amp; PhiM, <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a> BA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### removeFromOwner() {#a963bcbca3fecd1f5a2a4dea246e00b0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::removeFromOwner (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ad64ee563e178225490a0a8e262a4aba8">Ref</a> RA)</td>
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



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### removeUnusedPhis() {#ae2d2646041a1c1f7e05ea220e2b79dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::removeUnusedPhis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1452 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### reset() {#a6adad77c49bee969463a5fccb4f6cd2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### unlinkDefDF() {#a8e26d6a179743154dd2920e3b131dcf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::unlinkDefDF (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a10793004faece2bb74d3363b5f6ce96f">Def</a> DA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1683 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

### unlinkUseDF() {#ac8055d9ece9d0b6729d20b9c88b2c514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::rdf::DataFlowGraph::unlinkUseDF (<a href="/web-llvm/docs/api/namespaces/llvm/rdf/#abd774f5d3a81e00ffb690f4f5c0c82cf">Use</a> UA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BlockNodes {#a4ec227602630191edc1e368d312ea0ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;MachineBasicBlock *, Block&gt; llvm::rdf::DataFlowGraph::BlockNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### BuildCfg {#a15c30e38d2e4d603a821bd0467dc0caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Config llvm::rdf::DataFlowGraph::BuildCfg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### DefaultTOI {#a7bac24a2593cf0ba78aba1b5ce16d05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetOperandInfo&gt; llvm::rdf::DataFlowGraph::DefaultTOI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### LiveIns {#acc20b0f238313f1ea24a0fec84d16d66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterAggr llvm::rdf::DataFlowGraph::LiveIns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### LMI {#a304334326dc4a33b8ebb66dc5080c610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneMaskIndex llvm::rdf::DataFlowGraph::LMI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### MDF {#a2231c864afea6eec7591b6ee3b993b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominanceFrontier&amp; llvm::rdf::DataFlowGraph::MDF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### MDT {#abcfe9d846ae55ff085e9b272bdbfceb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineDominatorTree&amp; llvm::rdf::DataFlowGraph::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### Memory {#aa6df7d0610a945ab8663b5e6e2ad84d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeAllocator llvm::rdf::DataFlowGraph::Memory</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### MF {#a32746e872d0c4bc7b0a30ce043b595ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; llvm::rdf::DataFlowGraph::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### PRI {#a21d97b52b5758dbe183280724a7d835a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PhysicalRegisterInfo llvm::rdf::DataFlowGraph::PRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### ReservedRegs {#ab8149a6e14d4f0fc0b8da64f2272152e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::rdf::DataFlowGraph::ReservedRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### TheFunc {#aef11930e159344e7a209835fe093b78d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Func llvm::rdf::DataFlowGraph::TheFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### TII {#ac91ab379c5bf86a25604cfe80b9583d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; llvm::rdf::DataFlowGraph::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### TOI {#a56445a91ab0003593c22786f8360e8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetOperandInfo&amp; llvm::rdf::DataFlowGraph::TOI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### TrackedUnits {#a8d692986a02d693615e109d32db75c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::set&lt;unsigned&gt; llvm::rdf::DataFlowGraph::TrackedUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

### TRI {#a684f3b76c26e54ea488075fe62fbde8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; llvm::rdf::DataFlowGraph::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### IsCode() {#ac8b5aa2c1dd5ee4a4a8bf03730965c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;uint16_t Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::IsCode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> BA)</td>
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



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da3897c75682d603726fd11a4ce74fbfdf">llvm::rdf::NodeAttrs::Code</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#ad803998605d4a43c2eb44bd90ed19973">llvm::rdf::NodeBase::getKind</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a47f13a9bf570d95ac215312b5c77cc90">llvm::rdf::NodeBase::getType</a>.</p>

</div>
</div>

### IsDef() {#a264db9e61fcbc7db438de1f6a062a96a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::IsDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> BA)</td>
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



<p>Definition at line 825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121dacde70c4b68233671ba64c60b7ec08238">llvm::rdf::NodeAttrs::Def</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#ad803998605d4a43c2eb44bd90ed19973">llvm::rdf::NodeBase::getKind</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a47f13a9bf570d95ac215312b5c77cc90">llvm::rdf::NodeBase::getType</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1f251b754ed5bef25dc1f69e6bd845ea">llvm::rdf::NodeAttrs::Ref</a>.</p>

</div>
</div>

### IsPhi() {#a555e904e68d3d41e5f2db6beaabd49a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::IsPhi (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> BA)</td>
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



<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da3897c75682d603726fd11a4ce74fbfdf">llvm::rdf::NodeAttrs::Code</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#ad803998605d4a43c2eb44bd90ed19973">llvm::rdf::NodeBase::getKind</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a47f13a9bf570d95ac215312b5c77cc90">llvm::rdf::NodeBase::getType</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da0ae60988901d9b6e0499d07f94e8fc00">llvm::rdf::NodeAttrs::Phi</a>.</p>

</div>
</div>

### IsPreservingDef() {#a67533efd5231172ec9eb37c4ff10aec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::IsPreservingDef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a10793004faece2bb74d3363b5f6ce96f">Def</a> DA)</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da64fd1d9beb2a27391a05ee1d6d51b6e0">llvm::rdf::NodeAttrs::Preserving</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da19efcb0576040c1305e80dcc42758551">llvm::rdf::NodeAttrs::Undef</a>.</p>

</div>
</div>

### IsRef() {#a924c78446e6a6bca9371f02ae6c62b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;uint16_t Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::IsRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> BA)</td>
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



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#ad803998605d4a43c2eb44bd90ed19973">llvm::rdf::NodeBase::getKind</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a47f13a9bf570d95ac215312b5c77cc90">llvm::rdf::NodeBase::getType</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1f251b754ed5bef25dc1f69e6bd845ea">llvm::rdf::NodeAttrs::Ref</a>.</p>

</div>
</div>

### IsUse() {#a9a057fa5769de2acccd16b02326468b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::rdf::DataFlowGraph::IsUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/rdf/#ac54dd04d6e441d1b72195477e5bc1909">Node</a> BA)</td>
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



<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#ad803998605d4a43c2eb44bd90ed19973">llvm::rdf::NodeBase::getKind</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodebase/#a47f13a9bf570d95ac215312b5c77cc90">llvm::rdf::NodeBase::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121da1f251b754ed5bef25dc1f69e6bd845ea">llvm::rdf::NodeAttrs::Ref</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeattrs/#a96730c2fe7aaa0b753e7483d1e6a121daf9dd39c923393e08fbf871e15cc530b2">llvm::rdf::NodeAttrs::Use</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
