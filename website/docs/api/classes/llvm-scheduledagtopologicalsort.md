---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scheduledagtopologicalsort
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ScheduleDAGTopologicalSort` Class Reference

<p>This class can compute a topological ordering for SUnits and provides methods for dynamically updating the ordering as new edges are added. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ScheduleDAGTopologicalSort { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">llvm/CodeGen/ScheduleDAG.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; int &gt;::iterator <a href="#a8fdbdc9caa07928630964a81447d53d3">iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; int &gt;::const_iterator <a href="#a5fbba8dc1f6473b88462a3a451eb2254">const_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; int &gt;::reverse_iterator <a href="#a1ef75fbab584b21397a457d3216cd273">reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; int &gt;::const_reverse_iterator <a href="#afa732b62086d794c66688bec8fbb072a">const_reverse_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254598cfb0937d0bfd9a999c27370685">ScheduleDAGTopologicalSort</a> (std::vector&lt; SUnit &gt; &amp;SUnits, SUnit *ExitSU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ad30e09da64d0cb08f5391b3d5c0f9">AddSUnitWithoutPredecessors</a> (const SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> without predecessors to the end of the topological order. <a href="#a16ad30e09da64d0cb08f5391b3d5c0f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c5faa549f250a26b1303eb1a3ebd47">InitDAGTopologicalSorting</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates the initial topological ordering from the DAG to be scheduled. <a href="#a44c5faa549f250a26b1303eb1a3ebd47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a346955acdf30b0ecf7f58b3ba9e32129">GetSubGraph</a> (const SUnit &amp;StartSU, const SUnit &amp;TargetSU, bool &amp;Success)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an array of SUs that are both in the successor subtree of StartSU and in the predecessor subtree of TargetSU. <a href="#a346955acdf30b0ecf7f58b3ba9e32129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5fef42e8e1d446cf5e185b14dd4b8af">IsReachable</a> (const SUnit *SU, const SUnit *TargetSU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <span class="doxyComputerOutput">SU</span> is reachable from <span class="doxyComputerOutput">TargetSU</span>. <a href="#af5fef42e8e1d446cf5e185b14dd4b8af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142388e1eb164f473d3c10b3c582d51b">WillCreateCycle</a> (SUnit *TargetSU, SUnit *SU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if addPred(TargetSU, SU) creates a cycle. <a href="#a142388e1eb164f473d3c10b3c582d51b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47144792598184237de69d6b25b35175">AddPred</a> (SUnit *Y, SUnit *X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the topological ordering to accommodate an edge to be added from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">X</span> to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">Y</span>. <a href="#a47144792598184237de69d6b25b35175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8ee4f851bb0797b87ad841640ecadb5">AddPredQueued</a> (SUnit *Y, SUnit *X)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Queues an update to the topological ordering to accommodate an edge to be added from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">X</span> to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">Y</span>. <a href="#af8ee4f851bb0797b87ad841640ecadb5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a769ee13a9d9298d2c2b887dfae250">RemovePred</a> (SUnit *M, SUnit *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the topological ordering to accommodate an edge to be removed from the specified node <span class="doxyComputerOutput">N</span> from the predecessors of the current node <span class="doxyComputerOutput">M</span>. <a href="#a10a769ee13a9d9298d2c2b887dfae250">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a152853c43bedf99bebb1191e00c332a3">MarkDirty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark the ordering as temporarily broken, after a new node has been added. <a href="#a152853c43bedf99bebb1191e00c332a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8fdbdc9caa07928630964a81447d53d3">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6619b762bc4a668ff0fc63b0a9a9d405">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5fbba8dc1f6473b88462a3a451eb2254">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a4ef747547dfb531394cb06f8e09b3">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8fdbdc9caa07928630964a81447d53d3">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc48fc617dea5bb51be4a7210f63c25">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5fbba8dc1f6473b88462a3a451eb2254">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a442e991022349143be2837eb3e5b406f">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ef75fbab584b21397a457d3216cd273">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0ab86f00424ef15aa14542a57b2798d">rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afa732b62086d794c66688bec8fbb072a">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ef4102be66c620b1a26ba5d67e4918">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1ef75fbab584b21397a457d3216cd273">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1faf371bd07c60102c4cf7b334d5dac9">rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afa732b62086d794c66688bec8fbb072a">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2be15ea3a7108710d5d27090a25d121">rend</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48de8d81b70846e2f2719fae6d9049d6">DFS</a> (const SUnit *SU, int UpperBound, bool &amp;HasLoop)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes a DFS traversal and mark all nodes affected by the edge insertion. <a href="#a48de8d81b70846e2f2719fae6d9049d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a489e3bd0744a97566a92612b6aa7b6f2">Shift</a> (BitVector &amp;Visited, int LowerBound, int UpperBound)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reassigns topological indexes for the nodes in the DAG to preserve the topological ordering. <a href="#a489e3bd0744a97566a92612b6aa7b6f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e2a0cd74a0f64c2c8262f4274b8414">Allocate</a> (int n, int index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assigns the topological index to the node n. <a href="#ab4e2a0cd74a0f64c2c8262f4274b8414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d8111c26d2732dd6dccd1580e87159">FixOrder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fix the ordering, by either recomputing from scratch or by applying any outstanding updates. <a href="#a12d8111c26d2732dd6dccd1580e87159">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97edbd972621037ea10dc08c6f7b1641">SUnits</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a>'s SUnits. <a href="#a97edbd972621037ea10dc08c6f7b1641">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76834ff3ab6d978798433f04c440088">ExitSU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829421821f526ca6d8cecaa357f64d23">Dirty</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> *, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7591c184984f928b14119bbd1d71453d">Updates</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6386cda24043899cd1ae0c867faf6493">Index2Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps topological index to the node number. <a href="#a6386cda24043899cd1ae0c867faf6493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44a3eaf5189a2f23436cd03db91f76e2">Node2Index</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps the node number to its topological index. <a href="#a44a3eaf5189a2f23436cd03db91f76e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45f08437c6a8fe21a4c44ab311d9dbda">Visited</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>a set of nodes visited during a DFS traversal. <a href="#a45f08437c6a8fe21a4c44ab311d9dbda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class can compute a topological ordering for SUnits and provides methods for dynamically updating the ordering as new edges are added.</p>


<p>This allows a very fast implementation of IsReachable, for example.</p>


<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a5fbba8dc1f6473b88462a3a451eb2254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;int&gt;::const_iterator llvm::ScheduleDAGTopologicalSort::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#afa732b62086d794c66688bec8fbb072a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;int&gt;::const_reverse_iterator llvm::ScheduleDAGTopologicalSort::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### iterator {#a8fdbdc9caa07928630964a81447d53d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;int&gt;::iterator llvm::ScheduleDAGTopologicalSort::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### reverse\_iterator {#a1ef75fbab584b21397a457d3216cd273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt;int&gt;::reverse_iterator llvm::ScheduleDAGTopologicalSort::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ScheduleDAGTopologicalSort() {#a254598cfb0937d0bfd9a999c27370685}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGTopologicalSort::ScheduleDAGTopologicalSort (std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &gt; &amp; SUnits, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * ExitSU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 751 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddPred() {#a47144792598184237de69d6b25b35175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::AddPred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Y, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * X)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the topological ordering to accommodate an edge to be added from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">X</span> to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">Y</span>.</p>

<p>Declaration at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 550 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### AddPredQueued() {#af8ee4f851bb0797b87ad841640ecadb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::AddPredQueued (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * Y, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * X)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Queues an update to the topological ordering to accommodate an edge to be added from <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">X</span> to <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> <span class="doxyComputerOutput">Y</span>.</p>

<p>Declaration at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### AddSUnitWithoutPredecessors() {#a16ad30e09da64d0cb08f5391b3d5c0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::AddSUnitWithoutPredecessors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> without predecessors to the end of the topological order.</p>


<p>It also must be the first new node added to the DAG.</p>


<p>Declaration at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a25329a072c76c185b8c5ff530c632762">llvm::SUnit::NumPreds</a>.</p>

</div>
</div>

### begin() {#a6619b762bc4a668ff0fc63b0a9a9d405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ScheduleDAGTopologicalSort::begin ()</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### begin() {#aa6a4ef747547dfb531394cb06f8e09b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::ScheduleDAGTopologicalSort::begin ()</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### end() {#a2fc48fc617dea5bb51be4a7210f63c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::ScheduleDAGTopologicalSort::end ()</td>
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



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### end() {#a442e991022349143be2837eb3e5b406f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::ScheduleDAGTopologicalSort::end ()</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### GetSubGraph() {#a346955acdf30b0ecf7f58b3ba9e32129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; int &gt; ScheduleDAGTopologicalSort::GetSubGraph (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; StartSU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; TargetSU, bool &amp; Success)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an array of SUs that are both in the successor subtree of StartSU and in the predecessor subtree of TargetSU.</p>


<p>StartSU and TargetSU are not in the array. Success is false if TargetSU is not in the successor subtree of StartSU, else it is true.</p>


<p>Declaration at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a7406c398c67e53ee3937bf2b6df1c64e">llvm::SUnit::isBoundaryNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a32859a24aa7a3be269855b989d92a4b4">llvm::BitVector::resize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a62237ebe27691377a942abe7446332ec">llvm::BitVector::set</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a> and <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a15d63c566878e964c19139b2c76c0dab">llvm::BitVector::test</a>.</p>

</div>
</div>

### InitDAGTopologicalSorting() {#a44c5faa549f250a26b1303eb1a3ebd47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::InitDAGTopologicalSorting ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates the initial topological ordering from the DAG to be scheduled.</p>

<p>Declaration at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>

</div>
</div>

### IsReachable() {#af5fef42e8e1d446cf5e185b14dd4b8af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGTopologicalSort::IsReachable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * TargetSU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if <span class="doxyComputerOutput">SU</span> is reachable from <span class="doxyComputerOutput">TargetSU</span>.</p>

<p>Declaration at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 725 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#a3f708b119627541f144d703a1d183202">llvm::SUnit::NodeNum</a>.</p>


<p>Referenced by <a href="#a142388e1eb164f473d3c10b3c582d51b">WillCreateCycle</a>.</p>

</div>
</div>

### MarkDirty() {#a152853c43bedf99bebb1191e00c332a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGTopologicalSort::MarkDirty ()</td>
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

<p>Mark the ordering as temporarily broken, after a new node has been added.</p>

<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### rbegin() {#ad0ab86f00424ef15aa14542a57b2798d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::ScheduleDAGTopologicalSort::rbegin ()</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### rbegin() {#a19ef4102be66c620b1a26ba5d67e4918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::ScheduleDAGTopologicalSort::rbegin ()</td>
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



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### RemovePred() {#a10a769ee13a9d9298d2c2b887dfae250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::RemovePred (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * M, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the topological ordering to accommodate an edge to be removed from the specified node <span class="doxyComputerOutput">N</span> from the predecessors of the current node <span class="doxyComputerOutput">M</span>.</p>

<p>Declaration at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### rend() {#a1faf371bd07c60102c4cf7b334d5dac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::ScheduleDAGTopologicalSort::rend ()</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### rend() {#aa2be15ea3a7108710d5d27090a25d121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::ScheduleDAGTopologicalSort::rend ()</td>
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



<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### WillCreateCycle() {#a142388e1eb164f473d3c10b3c582d51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ScheduleDAGTopologicalSort::WillCreateCycle (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * TargetSU, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if addPred(TargetSU, SU) creates a cycle.</p>

<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a03a2dc5f9f321a2ce28f5c641dfe5455">llvm::SDep::getSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a6c89ab9b69b3bcaa536702845fd9542d">llvm::SDep::isAssignedRegDep</a>, <a href="#af5fef42e8e1d446cf5e185b14dd4b8af">IsReachable</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### Allocate() {#ab4e2a0cd74a0f64c2c8262f4274b8414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::Allocate (int n, int index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assigns the topological index to the node n.</p>

<p>Declaration at line 748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

### DFS() {#a48de8d81b70846e2f2719fae6d9049d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::DFS (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, int UpperBound, bool &amp; HasLoop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Makes a DFS traversal and mark all nodes affected by the edge insertion.</p>


<p>These nodes will later get new topological indexes by means of the Shift method.</p>


<p>Declaration at line 741 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

### FixOrder() {#a12d8111c26d2732dd6dccd1580e87159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::FixOrder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fix the ordering, by either recomputing from scratch or by applying any outstanding updates.</p>


<p>Uses a heuristic to estimate what will be cheaper.</p>


<p>Declaration at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

### Shift() {#a489e3bd0744a97566a92612b6aa7b6f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ScheduleDAGTopologicalSort::Shift (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Visited, int LowerBound, int UpperBound)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reassigns topological indexes for the nodes in the DAG to preserve the topological ordering.</p>

<p>Declaration at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>, definition at line 680 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Dirty {#a829421821f526ca6d8cecaa357f64d23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ScheduleDAGTopologicalSort::Dirty = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### ExitSU {#ad76834ff3ab6d978798433f04c440088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SUnit* llvm::ScheduleDAGTopologicalSort::ExitSU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Index2Node {#a6386cda24043899cd1ae0c867faf6493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;int&gt; llvm::ScheduleDAGTopologicalSort::Index2Node</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps topological index to the node number.</p>

<p>Definition at line 732 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Node2Index {#a44a3eaf5189a2f23436cd03db91f76e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;int&gt; llvm::ScheduleDAGTopologicalSort::Node2Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps the node number to its topological index.</p>

<p>Definition at line 734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### SUnits {#a97edbd972621037ea10dc08c6f7b1641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SUnit&gt;&amp; llvm::ScheduleDAGTopologicalSort::SUnits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A reference to the <a href="/web-llvm/docs/api/classes/llvm/scheduledag">ScheduleDAG</a>'s SUnits.</p>

<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Updates {#a7591c184984f928b14119bbd1d71453d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;SUnit *, SUnit *&gt;, 16&gt; llvm::ScheduleDAGTopologicalSort::Updates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

### Visited {#a45f08437c6a8fe21a4c44ab311d9dbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::ScheduleDAGTopologicalSort::Visited</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>a set of nodes visited during a DFS traversal.</p>

<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/scheduledag-h">ScheduleDAG.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledag-cpp">ScheduleDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
