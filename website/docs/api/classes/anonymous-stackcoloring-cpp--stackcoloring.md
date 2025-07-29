---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-stackcoloring-cpp-/stackcoloring
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `StackColoring` Class

<p><a href="/web-llvm/docs/api/classes/anonymous-stackcoloring-cpp-/stackcoloring">StackColoring</a> - A machine pass for merging disjoint stack allocations, marked by the LIFETIME_START and LIFETIME_END pseudo instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{StackColoring.cpp}::StackColoring { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba0a81e646e7bfcb6cf6f2d9cb764d7">LivenessMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, BlockLifetimeInfo &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps active slots (per bit) for each basic block. <a href="#aeba0a81e646e7bfcb6cf6f2d9cb764d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f4c6a26dd0fc3d4fed356823f8453a3">BlockBitVecMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used in collectMarkers. <a href="#a4f4c6a26dd0fc3d4fed356823f8453a3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c4d85591a3578b1b420dbde4c42580">StackColoring</a> (SlotIndexes *Indexes)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d6b0d6fae6fc47e5e354e6c3382938">run</a> (MachineFunction &amp;Func)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b02a9db581601dda7f4faad4e933e39">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debug. <a href="#a1b02a9db581601dda7f4faad4e933e39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ded4a94ddbb27252f02217befa76eb0">dumpIntervals</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6250e9734eb86b21892a686ab4fb25b8">dumpBB</a> (MachineBasicBlock *MBB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fbf3b1bbd4f8d43645cdb31c5df4567">dumpBV</a> (const char *tag, const BitVector &amp;BV) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac69d963ba237190c8208f310c1cb0e45">removeAllMarkers</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes all of the lifetime marker instructions from the function. <a href="#ac69d963ba237190c8208f310c1cb0e45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39e133b79aeab3ac6dace3fb804ceddf">collectMarkers</a> (unsigned NumSlot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scan the machine function and find all of the lifetime markers. <a href="#a39e133b79aeab3ac6dace3fb804ceddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4ea186aaa9b69e5344c93b732677ec">calculateLocalLiveness</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform the dataflow calculation and calculate the lifetime for each of the slots, based on the BEGIN/END vectors. <a href="#a8d4ea186aaa9b69e5344c93b732677ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d0909e976dfc868d13ec513b189a17">applyFirstUse</a> (int Slot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if we're using the first-use-begins-lifetime method for this slot (if FALSE, then the start marker is treated as start of lifetime). <a href="#a02d0909e976dfc868d13ec513b189a17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bbb75088b66780d62e1bfb73fd26537">isLifetimeStartOrEnd</a> (const MachineInstr &amp;MI, SmallVector&lt; int, 4 &gt; &amp;slots, bool &amp;isStart)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Examines the specified instruction and returns TRUE if the instruction represents the start or end of an interesting lifetime. <a href="#a2bbb75088b66780d62e1bfb73fd26537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd47c7be3573a6ac61078f1b5543558">calculateLiveIntervals</a> (unsigned NumSlots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct the <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> for the slots. <a href="#a1dd47c7be3573a6ac61078f1b5543558">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525b83fcc144faf424b7a13fa25c8bdd">remapInstructions</a> (DenseMap&lt; int, int &gt; &amp;SlotRemap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go over the machine function and change instructions which use stack slots to use the joint slots. <a href="#a525b83fcc144faf424b7a13fa25c8bdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe94386f11658e8b96e3f7a810e90401">removeInvalidSlotRanges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The input program may contain instructions which are not inside lifetime markers. <a href="#afe94386f11658e8b96e3f7a810e90401">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b088823e2eda3b62fa805530a05c3d">expungeSlotMap</a> (DenseMap&lt; int, int &gt; &amp;SlotRemap, unsigned NumSlots)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map entries which point to other entries to their destination. <a href="#a17b088823e2eda3b62fa805530a05c3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineframeinfo">MachineFrameInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f067fa92eae557d887a259cd4473056">MFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1969b3be516af7d49d65dc4e01088b77">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">LivenessMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d18763758b9e02a8b90b6544e74b10e">BlockLiveness</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a6e4a4de17b7dc7bf12592659de5eb">BasicBlocks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps serial numbers to basic blocks. <a href="#a28a6e4a4de17b7dc7bf12592659de5eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe3b60f85c7b2bad89636fc410811f5">BasicBlockNumbering</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps basic blocks to a serial number. <a href="#aefe3b60f85c7b2bad89636fc410811f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf06c25cbd660c617dafab6b6d65a22">Intervals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps slots to their use interval. <a href="#acbf06c25cbd660c617dafab6b6d65a22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, 4 &gt;, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dcc57a834d7e84d9a1c0f2a1f779e9d">LiveStarts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps slots to the points where they can become in-use. <a href="#a0dcc57a834d7e84d9a1c0f2a1f779e9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vninfo/#aa750a7f159760b9c378d930deb6a9837">VNInfo::Allocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5ccff269dcd58edec1b11c4d7ed5749">VNInfoAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> is used for the construction of <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>. <a href="#ab5ccff269dcd58edec1b11c4d7ed5749">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603d228e4b43c1dc04d4497e04194b78">Indexes</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> analysis object. <a href="#a603d228e4b43c1dc04d4497e04194b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c87d375f0618157ddc718da2963624a">Markers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of lifetime markers found. <a href="#a1c87d375f0618157ddc718da2963624a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a726bfc4c3b3759f51b091d8ef900f">InterestingSlots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the FI slots for which we have seen some sort of lifetime marker (either start or end). <a href="#a01a726bfc4c3b3759f51b091d8ef900f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956dc290dead4febb97579c22c7a1809">ConservativeSlots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FI slots that need to be handled conservatively (for these slots lifetime-start-on-first-use is disabled). <a href="#a956dc290dead4febb97579c22c7a1809">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9ca929b48b028ea79a547cf8ff98f7">NumIterations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of iterations taken during data flow analysis. <a href="#a3c9ca929b48b028ea79a547cf8ff98f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-stackcoloring-cpp-/stackcoloring">StackColoring</a> - A machine pass for merging disjoint stack allocations, marked by the LIFETIME_START and LIFETIME_END pseudo instructions.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### BlockBitVecMap {#a4f4c6a26dd0fc3d4fed356823f8453a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StackColoring.cpp}::StackColoring::BlockBitVecMap =  DenseMap&lt;const MachineBasicBlock *, BitVector&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used in collectMarkers.</p>

<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### LivenessMap {#aeba0a81e646e7bfcb6cf6f2d9cb764d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{StackColoring.cpp}::StackColoring::LivenessMap =  DenseMap&lt;const MachineBasicBlock *, BlockLifetimeInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps active slots (per bit) for each basic block.</p>

<p>Definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### StackColoring() {#af7c4d85591a3578b1b420dbde4c42580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{StackColoring.cpp}::StackColoring::StackColoring (<a href="/web-llvm/docs/api/classes/llvm/slotindexes">SlotIndexes</a> * Indexes)</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### run() {#a97d6b0d6fae6fc47e5e354e6c3382938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StackColoring::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp/#a53f7abea6827cac44c5cc170ed1b2429">DisableColoring</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a03503773241005f01b090b9862aad304">llvm::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a66ff664a97cd3c30de7e873335a0c075">llvm::LiveRange::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a4e12c0cb71a44b8822c5a35cbbe5c731">llvm::LiveRange::isLiveAtIndexes</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp/#a64335ebd86014e6660bc751627663b31">ProtectFromEscapedAllocas</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyFirstUse() {#a02d0909e976dfc868d13ec513b189a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{StackColoring.cpp}::StackColoring::applyFirstUse (int Slot)</td>
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

<p>Returns TRUE if we're using the first-use-begins-lifetime method for this slot (if FALSE, then the start marker is treated as start of lifetime).</p>

<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### calculateLiveIntervals() {#a1dd47c7be3573a6ac61078f1b5543558}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackColoring::calculateLiveIntervals (unsigned NumSlots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct the <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> for the slots.</p>

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### calculateLocalLiveness() {#a8d4ea186aaa9b69e5344c93b732677ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackColoring::calculateLocalLiveness ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform the dataflow calculation and calculate the lifetime for each of the slots, based on the BEGIN/END vectors.</p>


<p>Set the LifetimeLIVE_IN and LifetimeLIVE_OUT maps that represent which stack slots are live coming in and out blocks.</p>


<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### collectMarkers() {#a39e133b79aeab3ac6dace3fb804ceddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned StackColoring::collectMarkers (unsigned NumSlot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scan the machine function and find all of the lifetime markers.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the findings in the BEGIN and END vectors.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the number of markers found.</p></dd>
</dl>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### dump() {#a1b02a9db581601dda7f4faad4e933e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackColoring::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debug.</p>

<p>Definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### dumpBB() {#a6250e9734eb86b21892a686ab4fb25b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackColoring::dumpBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### dumpBV() {#a9fbf3b1bbd4f8d43645cdb31c5df4567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackColoring::dumpBV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * tag, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; BV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### dumpIntervals() {#a2ded4a94ddbb27252f02217befa76eb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void StackColoring::dumpIntervals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### expungeSlotMap() {#a17b088823e2eda3b62fa805530a05c3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackColoring::expungeSlotMap (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, int &gt; &amp; SlotRemap, unsigned NumSlots)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map entries which point to other entries to their destination.</p>


<p>A-&gt;B-&gt;C becomes A-&gt;C.</p>


<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### isLifetimeStartOrEnd() {#a2bbb75088b66780d62e1bfb73fd26537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StackColoring::isLifetimeStartOrEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 4 &gt; &amp; slots, bool &amp; isStart)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Examines the specified instruction and returns TRUE if the instruction represents the start or end of an interesting lifetime.</p>


<p>The slot or slots starting or ending are added to the vector "slots" and "isStart" is set accordingly.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if inst contains a lifetime start or end</p></dd>
</dl>


<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### remapInstructions() {#a525b83fcc144faf424b7a13fa25c8bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackColoring::remapInstructions (<a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, int &gt; &amp; SlotRemap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go over the machine function and change instructions which use stack slots to use the joint slots.</p>

<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### removeAllMarkers() {#ac69d963ba237190c8208f310c1cb0e45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool StackColoring::removeAllMarkers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Removes all of the lifetime marker instructions from the function.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if any markers were removed.</p></dd>
</dl>


<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### removeInvalidSlotRanges() {#afe94386f11658e8b96e3f7a810e90401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void StackColoring::removeInvalidSlotRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The input program may contain instructions which are not inside lifetime markers.</p>


<p>This can happen due to a bug in the compiler or due to a bug in user code (for example, returning a reference to a local variable). This procedure checks all of the instructions in the function and invalidates lifetime ranges which do not contain all of the instructions which access that frame slot.</p>


<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BasicBlockNumbering {#aefe3b60f85c7b2bad89636fc410811f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const MachineBasicBlock *, 8&gt; anonymous{StackColoring.cpp}::StackColoring::BasicBlockNumbering</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps basic blocks to a serial number.</p>

<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### BasicBlocks {#a28a6e4a4de17b7dc7bf12592659de5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const MachineBasicBlock *, int&gt; anonymous{StackColoring.cpp}::StackColoring::BasicBlocks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps serial numbers to basic blocks.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### BlockLiveness {#a1d18763758b9e02a8b90b6544e74b10e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LivenessMap anonymous{StackColoring.cpp}::StackColoring::BlockLiveness</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### ConservativeSlots {#a956dc290dead4febb97579c22c7a1809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{StackColoring.cpp}::StackColoring::ConservativeSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FI slots that need to be handled conservatively (for these slots lifetime-start-on-first-use is disabled).</p>

<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### Indexes {#a603d228e4b43c1dc04d4497e04194b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndexes* anonymous{StackColoring.cpp}::StackColoring::Indexes = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> analysis object.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### InterestingSlots {#a01a726bfc4c3b3759f51b091d8ef900f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{StackColoring.cpp}::StackColoring::InterestingSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the FI slots for which we have seen some sort of lifetime marker (either start or end).</p>

<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### Intervals {#acbf06c25cbd660c617dafab6b6d65a22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::unique_ptr&lt;LiveInterval&gt;, 16&gt; anonymous{StackColoring.cpp}::StackColoring::Intervals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps slots to their use interval.</p>


<p>Outside of this interval, slots values are either dead or <span class="doxyComputerOutput">undef</span> and they will not be written to.</p>


<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### LiveStarts {#a0dcc57a834d7e84d9a1c0f2a1f779e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;SmallVector&lt;SlotIndex, 4&gt;, 16&gt; anonymous{StackColoring.cpp}::StackColoring::LiveStarts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps slots to the points where they can become in-use.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### Markers {#a1c87d375f0618157ddc718da2963624a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 8&gt; anonymous{StackColoring.cpp}::StackColoring::Markers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of lifetime markers found.</p>


<p>These markers are to be removed once the coloring is done.</p>


<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### MF {#a1969b3be516af7d49d65dc4e01088b77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* anonymous{StackColoring.cpp}::StackColoring::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### MFI {#a9f067fa92eae557d887a259cd4473056}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo* anonymous{StackColoring.cpp}::StackColoring::MFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### NumIterations {#a3c9ca929b48b028ea79a547cf8ff98f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{StackColoring.cpp}::StackColoring::NumIterations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of iterations taken during data flow analysis.</p>

<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

### VNInfoAllocator {#ab5ccff269dcd58edec1b11c4d7ed5749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VNInfo::Allocator anonymous{StackColoring.cpp}::StackColoring::VNInfoAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> is used for the construction of <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/stackcoloring-cpp">StackColoring.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
