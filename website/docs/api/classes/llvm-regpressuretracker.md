---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/regpressuretracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RegPressureTracker` Class Reference

<p>Track the current register pressure at some position in the instruction stream, and remember the high water mark within the region traversed. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::RegPressureTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">llvm/CodeGen/RegisterPressure.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542eddcb7089b3159051d9a1c60eb872">RegPressureTracker</a> (IntervalPressure &amp;rp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3ba484282e153302812e51c411f271">RegPressureTracker</a> (RegionPressure &amp;rp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e57447ee6550f3ffcb4a432bd3dbab">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d044b599a2e3a1007e31a120105c9d7">init</a> (const MachineFunction *mf, const RegisterClassInfo *rci, const LiveIntervals *lis, const MachineBasicBlock *mbb, MachineBasicBlock::const_iterator pos, bool TrackLaneMasks, bool TrackUntiedDefs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup the <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a>. <a href="#a5d044b599a2e3a1007e31a120105c9d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dee9891ae8c828f279a6fe50e3265f2">addLiveRegs</a> (ArrayRef&lt; VRegMaskOrUnit &gt; Regs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Force liveness of virtual registers or physical register units. <a href="#a2dee9891ae8c828f279a6fe50e3265f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8743b2c5c27035fa002ef69e9df50c72">getPos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the MI position corresponding to this register pressure. <a href="#a8743b2c5c27035fa002ef69e9df50c72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7f11867d76f00e7a6453ef5b9a129a">setPos</a> (MachineBasicBlock::const_iterator Pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20a8136fbbb55939ae03e734232ce942">recede</a> (SmallVectorImpl&lt; VRegMaskOrUnit &gt; *LiveUses=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recede across the previous instruction. <a href="#a20a8136fbbb55939ae03e734232ce942">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126f33e8085746e4f69b4411b61102dc">recede</a> (const RegisterOperands &amp;RegOpers, SmallVectorImpl&lt; VRegMaskOrUnit &gt; *LiveUses=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recede across the previous instruction. <a href="#a126f33e8085746e4f69b4411b61102dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354c230443b1586633f5697aec0bcd8e">recedeSkipDebugValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recede until we find an instruction which is not a DebugValue. <a href="#a354c230443b1586633f5697aec0bcd8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99487c5b550882cba98d817d47cc3fc0">advance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance across the current instruction. <a href="#a99487c5b550882cba98d817d47cc3fc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147da0e049b6b53046afe6825447eeaa">advance</a> (const RegisterOperands &amp;RegOpers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance across the current instruction. <a href="#a147da0e049b6b53046afe6825447eeaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the region boundaries and recored live ins and live outs. <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a474e65b5df97bf9cf404aa9b85eb6262">initLiveThru</a> (const RegPressureTracker &amp;RPTracker)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize the LiveThru pressure set based on the untied defs found in RPTracker. <a href="#a474e65b5df97bf9cf404aa9b85eb6262">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d055efabadfeaf759463d4edf2c2207">initLiveThru</a> (ArrayRef&lt; unsigned &gt; PressureSet)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy an existing live thru pressure result. <a href="#a4d055efabadfeaf759463d4edf2c2207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f7335c3bd0a223b50b5bd4839ab7b24">getLiveThru</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d9f679a1642e0af0bd33637d808114">getPressure</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the resulting register pressure over the traversed region. <a href="#a29d9f679a1642e0af0bd33637d808114">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a988d1db6dc744be09db6371a17e7f154">getPressure</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; unsigned &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd579b6c2156091eb3134238f13053e0">getRegSetPressureAtPos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the register set pressure at the current position, which may be less than the pressure across the traversed region. <a href="#acd579b6c2156091eb3134238f13053e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this pressure result have a valid top position and live ins. <a href="#aa04a52c4ce53301c9dfca990019c257f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this pressure result have a valid bottom position and live outs. <a href="#a6b2a46b62294d7923901959892016838">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8759dfc94f9731598942bbbda6280dfe">closeTop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the boundary for the top of the region and summarize live ins. <a href="#a8759dfc94f9731598942bbbda6280dfe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a204b8f2de53bb48cc63b152400c3fdb6">closeBottom</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the boundary for the bottom of the region and summarize live outs. <a href="#a204b8f2de53bb48cc63b152400c3fdb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a3118fb6bd46e397256b3c9794b61c">getMaxUpwardPressureDelta</a> (const MachineInstr *MI, PressureDiff *PDiff, RegPressureDelta &amp;Delta, ArrayRef&lt; PressureChange &gt; CriticalPSets, ArrayRef&lt; unsigned &gt; MaxPressureLimit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consider the pressure increase caused by traversing this instruction bottom-up. <a href="#a41a3118fb6bd46e397256b3c9794b61c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7a0688faef62284ad684e70f342b3da">getUpwardPressureDelta</a> (const MachineInstr *MI, PressureDiff &amp;PDiff, RegPressureDelta &amp;Delta, ArrayRef&lt; PressureChange &gt; CriticalPSets, ArrayRef&lt; unsigned &gt; MaxPressureLimit) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the fast version of querying register pressure that does not directly depend on current liveness. <a href="#af7a0688faef62284ad684e70f342b3da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972fa38378a3d49a9bb48ca584621438">getMaxDownwardPressureDelta</a> (const MachineInstr *MI, RegPressureDelta &amp;Delta, ArrayRef&lt; PressureChange &gt; CriticalPSets, ArrayRef&lt; unsigned &gt; MaxPressureLimit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consider the pressure increase caused by traversing this instruction top-down. <a href="#a972fa38378a3d49a9bb48ca584621438">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25c90e70c6038993c4ef93aff49fb987">getMaxPressureDelta</a> (const MachineInstr *MI, RegPressureDelta &amp;Delta, ArrayRef&lt; PressureChange &gt; CriticalPSets, ArrayRef&lt; unsigned &gt; MaxPressureLimit)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the pressure set with the most change beyond its pressure limit after traversing this instruction either upward or downward depending on the closed end of the current region. <a href="#a25c90e70c6038993c4ef93aff49fb987">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad552b6e557acce957b3bd5a1960a53dd">getUpwardPressure</a> (const MachineInstr *MI, std::vector&lt; unsigned &gt; &amp;PressureResult, std::vector&lt; unsigned &gt; &amp;MaxPressureResult)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pressure of each PSet after traversing this instruction bottom-up. <a href="#ad552b6e557acce957b3bd5a1960a53dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1bfd03ca8fa96ab674c7f7b620dd8a6">getDownwardPressure</a> (const MachineInstr *MI, std::vector&lt; unsigned &gt; &amp;PressureResult, std::vector&lt; unsigned &gt; &amp;MaxPressureResult)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the pressure of each PSet after traversing this instruction top-down. <a href="#ac1bfd03ca8fa96ab674c7f7b620dd8a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20bbe14c4c52bcb57b892d36c9517aa2">getPressureAfterInst</a> (const MachineInstr *MI, std::vector&lt; unsigned &gt; &amp;PressureResult, std::vector&lt; unsigned &gt; &amp;MaxPressureResult)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77304a98095575cf08c43d237137c77e">hasUntiedDef</a> (Register VirtReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c8a8fa22cf5ab29fe7441b1fbeabff">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a> (Register RegUnit, LaneBitmask PreviousMask, LaneBitmask NewMask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb147ca865dee711c206a23c2fbda878">decreaseRegPressure</a> (Register RegUnit, LaneBitmask PreviousMask, LaneBitmask NewMask)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a5fc111668db50846814135e73973a">discoverLiveOut</a> (VRegMaskOrUnit Pair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add Reg to the live out set and increase max pressure. <a href="#ae3a5fc111668db50846814135e73973a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf29a336b68eceac55ca50d73e19c9e">discoverLiveIn</a> (VRegMaskOrUnit Pair)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add Reg to the live in set and increase max pressure. <a href="#a1cf29a336b68eceac55ca50d73e19c9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb935d3f3c59d7ad1049e01788c65f34">getCurrSlot</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> for the first nondebug instruction including or after the current position. <a href="#acb935d3f3c59d7ad1049e01788c65f34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a> (ArrayRef&lt; VRegMaskOrUnit &gt; DeadDefs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0885ecf357ddad3594c9a2a5a9527f2">bumpUpwardPressure</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the upward impact of a single instruction on current register pressure. <a href="#ab0885ecf357ddad3594c9a2a5a9527f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a> (const MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the downward impact of a single instruction on current register pressure. <a href="#a2b8b6196a7458b6a84480f03e2f1355d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60e96ac40c51e2ad7e24f9776fda71d1">discoverLiveInOrOut</a> (VRegMaskOrUnit Pair, SmallVectorImpl&lt; VRegMaskOrUnit &gt; &amp;LiveInOrOut)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acba0d5ed53c0ebfa11cc3310e6aef4b1">getLastUsedLanes</a> (Register RegUnit, SlotIndex Pos) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9551d47c4a9bc95eec03d02f11dfef3b">getLiveLanesAt</a> (Register RegUnit, SlotIndex Pos) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b14ec0777ac642d3403470e0753533">getLiveThroughAt</a> (Register RegUnit, SlotIndex Pos) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dee4778d10158e05a68ca73cc0156c7">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae019366b5eb82ee5d10090270e39253">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bea46c11d6e26aedcd74e713b0e2af">RCI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ba22893f4de8b73273bc832f1b0593">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2584dc4c22eae33b190ca06bc4c60ad3">LIS</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9abae53ab9832f1a9b4bad45a91806ea">MBB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We currently only allow pressure tracking within a block. <a href="#a9abae53ab9832f1a9b4bad45a91806ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14611e92832041d5ab0ff4ecee241f16">P</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track the max pressure within the region traversed so far. <a href="#a14611e92832041d5ab0ff4ecee241f16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c975f8df4fe00450049e2e95da4b7f">RequireIntervals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run in two modes dependending on whether constructed with <a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a> or <a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a>. <a href="#a07c975f8df4fe00450049e2e95da4b7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae059ef7d2d73a1ff8e7f4257810349de">TrackUntiedDefs</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if UntiedDefs will be populated. <a href="#ae059ef7d2d73a1ff8e7f4257810349de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473dbcaa25e77f7ca125638fe18d2719">TrackLaneMasks</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if lanemasks should be tracked. <a href="#a473dbcaa25e77f7ca125638fe18d2719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a951c767eaffa84584e349e927a370932">CurrPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> pressure corresponds to liveness before this instruction iterator. <a href="#a951c767eaffa84584e349e927a370932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4c83da5c9fd15bb3264cffb2701e4cc">CurrSetPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pressure map indexed by pressure set <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, not class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#ae4c83da5c9fd15bb3264cffb2701e4cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveregset">LiveRegSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f88ec4beeb8edde81bc6417528664c">LiveRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of live registers. <a href="#a39f88ec4beeb8edde81bc6417528664c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sparseset">SparseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc60826cad75a1fc9fbbfd0a94a7ce1">UntiedDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of vreg defs that start a live range. <a href="#a8dc60826cad75a1fc9fbbfd0a94a7ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1462fb4a4d1495c81900a157b0d14c">LiveThruPressure</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Live-through pressure. <a href="#ade1462fb4a4d1495c81900a157b0d14c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Track the current register pressure at some position in the instruction stream, and remember the high water mark within the region traversed.</p>


<p>This does not automatically consider live-through ranges. The client may independently adjust for global liveness.</p>


<p>Each <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> only works within a <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>. Pressure can be tracked across a larger region by storing a <a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> result at each block boundary and explicitly adjusting pressure to account for block live-in and live-out register sets.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> holds a reference to a <a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a> result that it computes incrementally. During downward tracking, P.BottomIdx or P.BottomPos is invalid until it reaches the end of the block or <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion()</a> is explicitly called. Similarly, P.TopIdx is invalid during upward tracking. Changing direction has the side effect of closing region, and traversing past TopIdx or BottomIdx reopens it.</p>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegPressureTracker() {#a542eddcb7089b3159051d9a1c60eb872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegPressureTracker::RegPressureTracker (<a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a> &amp; rp)</td>
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



<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#a474e65b5df97bf9cf404aa9b85eb6262">initLiveThru</a>.</p>

</div>
</div>

### RegPressureTracker() {#a4e3ba484282e153302812e51c411f271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegPressureTracker::RegPressureTracker (<a href="/web-llvm/docs/api/structs/llvm/regionpressure">RegionPressure</a> &amp; rp)</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addLiveRegs() {#a2dee9891ae8c828f279a6fe50e3265f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::addLiveRegs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; Regs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Force liveness of virtual registers or physical register units.</p>


<p>Force liveness of registers.</p>


<p>Particularly useful to initialize the livein/out state of the tracker before the first call to advance/recede.</p>


<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Reference <a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a3fb8c57a2275283cbb376004421318da">computeLiveOuts</a>.</p>

</div>
</div>

### advance() {#a99487c5b550882cba98d817d47cc3fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::advance ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance across the current instruction.</p>

<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="#a99487c5b550882cba98d817d47cc3fc0">advance</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="#acb935d3f3c59d7ad1049e01788c65f34">getCurrSlot</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a99487c5b550882cba98d817d47cc3fc0">advance</a>.</p>

</div>
</div>

### advance() {#a147da0e049b6b53046afe6825447eeaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::advance (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registeroperands">RegisterOperands</a> &amp; RegOpers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance across the current instruction.</p>


<p>This is a "low-level" variant of <a href="#a99487c5b550882cba98d817d47cc3fc0">advance()</a> which takes precomputed <a href="/web-llvm/docs/api/classes/llvm/registeroperands">RegisterOperands</a> of the instruction.</p>


<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 885 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a>, <a href="#a8759dfc94f9731598942bbbda6280dfe">closeTop</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a797ecc0909ee51516d50dd74698515b5">llvm::RegisterOperands::DeadDefs</a>, <a href="#aeb147ca865dee711c206a23c2fbda878">decreaseRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a2b640124aa4a430ee67d5409120e4deb">llvm::RegisterOperands::Defs</a>, <a href="#a1cf29a336b68eceac55ca50d73e19c9e">discoverLiveIn</a>, <a href="#acb935d3f3c59d7ad1049e01788c65f34">getCurrSlot</a>, <a href="#acba0d5ed53c0ebfa11cc3310e6aef4b1">getLastUsedLanes</a>, <a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a>, <a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a> and <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acf9cb57c0c3b81e758a2af8aca736842">llvm::RegisterOperands::Uses</a>.</p>

</div>
</div>

### closeBottom() {#a204b8f2de53bb48cc63b152400c3fdb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::closeBottom ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the boundary for the bottom of the region and summarize live outs.</p>

<p>Declaration at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#acb935d3f3c59d7ad1049e01788c65f34">getCurrSlot</a>.</p>


<p>Referenced by <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion</a> and <a href="#a354c230443b1586633f5697aec0bcd8e">recedeSkipDebugValues</a>.</p>

</div>
</div>

### closeRegion() {#a1844e0ed5cc8c90d7afaad0bea1e48d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::closeRegion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the region boundaries and recored live ins and live outs.</p>


<p>Finalize the region boundaries and record live ins and live outs.</p>


<p>Declaration at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a204b8f2de53bb48cc63b152400c3fdb6">closeBottom</a>, <a href="#a8759dfc94f9731598942bbbda6280dfe">closeTop</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a> and <a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### closeTop() {#a8759dfc94f9731598942bbbda6280dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::closeTop ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the boundary for the top of the region and summarize live ins.</p>

<p>Declaration at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#acb935d3f3c59d7ad1049e01788c65f34">getCurrSlot</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a> and <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion</a>.</p>

</div>
</div>

### decreaseRegPressure() {#aeb147ca865dee711c206a23c2fbda878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::decreaseRegPressure (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> PreviousMask, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> NewMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a58eaab8d4f7a677b915d22694d73f286">decreaseSetPressure</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>, <a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a>, <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a>, <a href="#ab0885ecf357ddad3594c9a2a5a9527f2">bumpUpwardPressure</a> and <a href="#a126f33e8085746e4f69b4411b61102dc">recede</a>.</p>

</div>
</div>

### dump() {#a56c8a8fa22cf5ab29fe7441b1fbeabff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void RegPressureTracker::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb6fca77863850136760be488d6ea345">llvm::dumpRegSetPressure</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a> and <a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a>.</p>

</div>
</div>

### getDownwardPressure() {#ac1bfd03ca8fa96ab674c7f7b620dd8a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::getDownwardPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, std::vector&lt; unsigned &gt; &amp; PressureResult, std::vector&lt; unsigned &gt; &amp; MaxPressureResult)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the pressure of each PSet after traversing this instruction top-down.</p>

<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a20bbe14c4c52bcb57b892d36c9517aa2">getPressureAfterInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a>.</p>

</div>
</div>

### getLiveThru() {#a1f7335c3bd0a223b50b5bd4839ab7b24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; llvm::RegPressureTracker::getLiveThru ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### getMaxDownwardPressureDelta() {#a972fa38378a3d49a9bb48ca584621438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::getMaxDownwardPressureDelta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; Delta, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &gt; CriticalPSets, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; MaxPressureLimit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consider the pressure increase caused by traversing this instruction top-down.</p>


<p>Find the pressure set with the most change beyond its pressure limit based on the tracker's current pressure, and record the number of excess register units of that pressure set introduced by this instruction.</p>


<p>Find the register class with the most change in its pressure limit based on the tracker's current pressure, and return the number of excess register units of that pressure set introduced by this instruction.</p>


<p>This assumes that the current LiveIn set is sufficient.</p>


<p>This is expensive for an on-the-fly query because it calls bumpDownwardPressure to recompute the pressure sets based on current liveness. We don't yet have a fast version of downward pressure tracking analogous to getUpwardPressureDelta.</p>


<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1335 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a013f10c0323064cf28c1aed647c0b478">computeExcessPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a1eef24878593ee0080b20b96ce3eb4c4">llvm::PressureChange::getUnitInc</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a25c90e70c6038993c4ef93aff49fb987">getMaxPressureDelta</a> and <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>.</p>

</div>
</div>

### getMaxPressureDelta() {#a25c90e70c6038993c4ef93aff49fb987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegPressureTracker::getMaxPressureDelta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; Delta, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &gt; CriticalPSets, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; MaxPressureLimit)</td>
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

<p>Find the pressure set with the most change beyond its pressure limit after traversing this instruction either upward or downward depending on the closed end of the current region.</p>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a972fa38378a3d49a9bb48ca584621438">getMaxDownwardPressureDelta</a>, <a href="#a41a3118fb6bd46e397256b3c9794b61c">getMaxUpwardPressureDelta</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a>, <a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/convergingvliwscheduler/#aba911ea9e1feddf77d47ae9112f534e0">llvm::ConvergingVLIWScheduler::readyQueueVerboseDump</a>.</p>

</div>
</div>

### getMaxUpwardPressureDelta() {#a41a3118fb6bd46e397256b3c9794b61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::getMaxUpwardPressureDelta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> * PDiff, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; Delta, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &gt; CriticalPSets, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; MaxPressureLimit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consider the pressure increase caused by traversing this instruction bottom-up.</p>


<p>Find the pressure set with the most change beyond its pressure limit based on the tracker's current pressure, and record the number of excess register units of that pressure set introduced by this instruction.</p>


<p>Find the pressure set with the most change beyond its pressure limit based on the tracker's current pressure, and return the change in number of register units of that pressure set introduced by this instruction.</p>


<p>This assumes that the current LiveOut set is sufficient.</p>


<p>This is expensive for an on-the-fly query because it calls bumpUpwardPressure to recompute the pressure sets based on current liveness. This mainly exists to verify correctness, e.g. with -verify-misched. getUpwardPressureDelta is the fast version of this query that uses the per-SUnit cache of the <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a>.</p>


<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1086 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ab0885ecf357ddad3594c9a2a5a9527f2">bumpUpwardPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a013f10c0323064cf28c1aed647c0b478">computeExcessPressureDelta</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a822aec28298cd2dc8f346d4753a4154b">computeMaxPressureDelta</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#a86962b61c920a437e06eda5dafd929d5">llvm::PressureDiff::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#ad47247ae6eaa7104e4d4ef6e002840f9">llvm::PressureChange::getPSet</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a1eef24878593ee0080b20b96ce3eb4c4">llvm::PressureChange::getUnitInc</a>, <a href="#af7a0688faef62284ad684e70f342b3da">getUpwardPressureDelta</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a488d33ac015981b0f8e2086fcbd49db2">llvm::PressureChange::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a25c90e70c6038993c4ef93aff49fb987">getMaxPressureDelta</a> and <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>.</p>

</div>
</div>

### getPos() {#a8743b2c5c27035fa002ef69e9df50c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_iterator llvm::RegPressureTracker::getPos ()</td>
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

<p>Get the MI position corresponding to this register pressure.</p>

<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### getPressure() {#a29d9f679a1642e0af0bd33637d808114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterPressure &amp; llvm::RegPressureTracker::getPressure ()</td>
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

<p>Get the resulting register pressure over the traversed region.</p>


<p>This result is complete if <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion()</a> was explicitly invoked.</p>


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### getPressure() {#a988d1db6dc744be09db6371a17e7f154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterPressure &amp; llvm::RegPressureTracker::getPressure ()</td>
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



<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### getPressureAfterInst() {#a20bbe14c4c52bcb57b892d36c9517aa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegPressureTracker::getPressureAfterInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, std::vector&lt; unsigned &gt; &amp; PressureResult, std::vector&lt; unsigned &gt; &amp; MaxPressureResult)</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac1bfd03ca8fa96ab674c7f7b620dd8a6">getDownwardPressure</a>, <a href="#ad552b6e557acce957b3bd5a1960a53dd">getUpwardPressure</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a>, <a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getRegSetPressureAtPos() {#acd579b6c2156091eb3134238f13053e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; unsigned &gt; &amp; llvm::RegPressureTracker::getRegSetPressureAtPos ()</td>
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

<p>Get the register set pressure at the current position, which may be less than the pressure across the traversed region.</p>

<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnschedstrategy/#a2777a131d60f64dbebce2d7116f198c7">llvm::GCNSchedStrategy::pickNodeFromQueue</a>.</p>

</div>
</div>

### getUpwardPressure() {#ad552b6e557acce957b3bd5a1960a53dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::getUpwardPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, std::vector&lt; unsigned &gt; &amp; PressureResult, std::vector&lt; unsigned &gt; &amp; MaxPressureResult)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the pressure of each PSet after traversing this instruction bottom-up.</p>

<p>Declaration at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#ab0885ecf357ddad3594c9a2a5a9527f2">bumpUpwardPressure</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a20bbe14c4c52bcb57b892d36c9517aa2">getPressureAfterInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnschedstrategy-cpp/#ad8dc903ae7dd7695e082f3d3fb80be92">getRegisterPressures</a>.</p>

</div>
</div>

### getUpwardPressureDelta() {#af7a0688faef62284ad684e70f342b3da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::getUpwardPressureDelta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/pressurediff">PressureDiff</a> &amp; PDiff, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta">RegPressureDelta</a> &amp; Delta, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/pressurechange">PressureChange</a> &gt; CriticalPSets, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; MaxPressureLimit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the fast version of querying register pressure that does not directly depend on current liveness.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Delta</td>
<td class="doxyParamItemDescription"><p>captures information needed for heuristics.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CriticalPSets</td>
<td class="doxyParamItemDescription"><p>Are the pressure sets that are known to exceed some limit within the region, not necessarily at the current position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MaxPressureLimit</td>
<td class="doxyParamItemDescription"><p>Is the max pressure within the region, not necessarily at the current position.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#ade51f35b5a03cbdcbaa15c8e715adfbe">llvm::PressureDiff::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a277da5755f2b30ebcebdba51d0de1acf">llvm::RegPressureDelta::CriticalMax</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#a589e1a7e9a8a095d8d01ff8ba32b3d14">llvm::RegPressureDelta::CurrentMax</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurediff/#aaeea35b94bc1d5d20885feab986421f6">llvm::PressureDiff::end</a>, <a href="/web-llvm/docs/api/structs/llvm/regpressuredelta/#aff9c3b403c6d4af795dd8be1c9612240">llvm::RegPressureDelta::Excess</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a488d33ac015981b0f8e2086fcbd49db2">llvm::PressureChange::isValid</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/pressurechange/#a4b74a0d0d1bc2e22fa7376eda3fdd85f">llvm::PressureChange::setUnitInc</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a41a3118fb6bd46e397256b3c9794b61c">getMaxUpwardPressureDelta</a> and <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#ab0d12eb20352f092840f7f8df60abe26">llvm::GenericScheduler::initCandidate</a>.</p>

</div>
</div>

### hasUntiedDef() {#a77304a98095575cf08c43d237137c77e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegPressureTracker::hasUntiedDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
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



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>Referenced by <a href="#a474e65b5df97bf9cf404aa9b85eb6262">initLiveThru</a>.</p>

</div>
</div>

### increaseRegPressure() {#adef3cd5d80fc7eb1bf88f3c9586d6801}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::increaseRegPressure (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> PreviousMask, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a> NewMask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/classes/llvm/psetiterator/#a7468f7aa9ad819d0d0294cc66da0c9e8">llvm::PSetIterator::getWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/psetiterator/#adca9aa81c4b0432673b64c7c42611df5">llvm::PSetIterator::isValid</a> and <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>.</p>


<p>Referenced by <a href="#a2dee9891ae8c828f279a6fe50e3265f2">addLiveRegs</a>, <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>, <a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a>, <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a>, <a href="#ab0885ecf357ddad3594c9a2a5a9527f2">bumpUpwardPressure</a> and <a href="#a126f33e8085746e4f69b4411b61102dc">recede</a>.</p>

</div>
</div>

### init() {#a5d044b599a2e3a1007e31a120105c9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * mf, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> * rci, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> * lis, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * mbb, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> pos, bool TrackLaneMasks, bool TrackUntiedDefs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setup the <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a>.</p>


<p>TODO: Add support for pressure without <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a>.</p>


<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a> and <a href="#ac9e57447ee6550f3ffcb4a432bd3dbab">reset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### initLiveThru() {#a474e65b5df97bf9cf404aa9b85eb6262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::initLiveThru (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker">RegPressureTracker</a> &amp; RPTracker)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize the LiveThru pressure set based on the untied defs found in RPTracker.</p>


<p>The register tracker is unaware of global liveness so ignores normal live-thru ranges.</p>


<p>However, two-address or coalesced chains can also lead to live ranges with no holes. Count these to inform heuristics that we can never drop below this pressure.</p>


<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="#a77304a98095575cf08c43d237137c77e">hasUntiedDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a217ca2f956651626db2bf0fdf48bd82d">increaseSetPressure</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit/#a77670492e7be5b863b106969e8963a47">llvm::VRegMaskOrUnit::LaneMask</a>, <a href="#a542eddcb7089b3159051d9a1c60eb872">RegPressureTracker</a> and <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit/#a850b5c0b8b36bb79d7bb84f4bb96f91e">llvm::VRegMaskOrUnit::RegUnit</a>.</p>

</div>
</div>

### initLiveThru() {#a4d055efabadfeaf759463d4edf2c2207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegPressureTracker::initLiveThru (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; PressureSet)</td>
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

<p>Copy an existing live thru pressure result.</p>

<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>.</p>

</div>
</div>

### isBottomClosed() {#a6b2a46b62294d7923901959892016838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegPressureTracker::isBottomClosed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does this pressure result have a valid bottom position and live outs.</p>

<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>, <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion</a>, <a href="#a56c8a8fa22cf5ab29fe7441b1fbeabff">dump</a>, <a href="#a25c90e70c6038993c4ef93aff49fb987">getMaxPressureDelta</a>, <a href="#a20bbe14c4c52bcb57b892d36c9517aa2">getPressureAfterInst</a>, <a href="#a474e65b5df97bf9cf404aa9b85eb6262">initLiveThru</a> and <a href="#a354c230443b1586633f5697aec0bcd8e">recedeSkipDebugValues</a>.</p>

</div>
</div>

### isTopClosed() {#aa04a52c4ce53301c9dfca990019c257f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RegPressureTracker::isTopClosed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does this pressure result have a valid top position and live ins.</p>

<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>, <a href="#a1844e0ed5cc8c90d7afaad0bea1e48d7">closeRegion</a>, <a href="#a56c8a8fa22cf5ab29fe7441b1fbeabff">dump</a>, <a href="#a25c90e70c6038993c4ef93aff49fb987">getMaxPressureDelta</a>, <a href="#a20bbe14c4c52bcb57b892d36c9517aa2">getPressureAfterInst</a> and <a href="#a354c230443b1586633f5697aec0bcd8e">recedeSkipDebugValues</a>.</p>

</div>
</div>

### recede() {#a20a8136fbbb55939ae03e734232ce942}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::recede (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; * LiveUses=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recede across the previous instruction.</p>

<p>Declaration at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a20a8136fbbb55939ae03e734232ce942">recede</a> and <a href="#a354c230443b1586633f5697aec0bcd8e">recedeSkipDebugValues</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="#a20a8136fbbb55939ae03e734232ce942">recede</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### recede() {#a126f33e8085746e4f69b4411b61102dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::recede (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registeroperands">RegisterOperands</a> &amp; RegOpers, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; * LiveUses=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recede across the previous instruction.</p>


<p>This "low-level" variant assumes that <a href="#a354c230443b1586633f5697aec0bcd8e">recedeSkipDebugValues()</a> was called previously and takes precomputed <a href="/web-llvm/docs/api/classes/llvm/registeroperands">RegisterOperands</a> for the instruction.</p>


<p>If LiveUses is provided, record any RegUnits that are made live by the current instruction's uses. This includes registers that are both defined and used by the instruction. If a pressure difference pointer is provided record the changes is pressure caused by this instruction independent of liveness.</p>


<p>Declaration at line 429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#adfcb78856461567d0d6f7012aee7a89a">addRegLanes</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a797ecc0909ee51516d50dd74698515b5">llvm::RegisterOperands::DeadDefs</a>, <a href="#aeb147ca865dee711c206a23c2fbda878">decreaseRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a2b640124aa4a430ee67d5409120e4deb">llvm::RegisterOperands::Defs</a>, <a href="#ae3a5fc111668db50846814135e73973a">discoverLiveOut</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#ad8b14ec0777ac642d3403470e0753533">getLiveThroughAt</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a217ca2f956651626db2bf0fdf48bd82d">increaseSetPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a7241534b422b4edd167aedf565fb8d5c">removeRegLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ab068414df7b5a70b9ed5e2c342435703">setRegZero</a> and <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acf9cb57c0c3b81e758a2af8aca736842">llvm::RegisterOperands::Uses</a>.</p>

</div>
</div>

### recedeSkipDebugValues() {#a354c230443b1586633f5697aec0bcd8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::recedeSkipDebugValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recede until we find an instruction which is not a DebugValue.</p>

<p>Declaration at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 841 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a204b8f2de53bb48cc63b152400c3fdb6">closeBottom</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="#a6b2a46b62294d7923901959892016838">isBottomClosed</a>, <a href="#aa04a52c4ce53301c9dfca990019c257f">isTopClosed</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae74dcdb801fe44b3840dd93e6c395066">llvm::prev_nodbg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="#a20a8136fbbb55939ae03e734232ce942">recede</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#acba682e84de176f762ddc4d774819cae">llvm::PPCInstrInfo::shouldReduceRegisterPressure</a>.</p>

</div>
</div>

### reset() {#ac9e57447ee6550f3ffcb4a432bd3dbab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#aa1555194b9f176612b04fbd38f49b40d">llvm::LiveRange::clear</a> and <a href="#ac9e57447ee6550f3ffcb4a432bd3dbab">reset</a>.</p>


<p>Referenced by <a href="#a5d044b599a2e3a1007e31a120105c9d7">init</a> and <a href="#ac9e57447ee6550f3ffcb4a432bd3dbab">reset</a>.</p>

</div>
</div>

### setPos() {#a1d7f11867d76f00e7a6453ef5b9a129a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::RegPressureTracker::setPos (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> Pos)</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### bumpDeadDefs() {#a4cd7dac51234f69ca2c32b7e22f8d27d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::bumpDeadDefs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; DeadDefs)</td>
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



<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 734 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="#aeb147ca865dee711c206a23c2fbda878">decreaseRegPressure</a> and <a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>, <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a>, <a href="#ab0885ecf357ddad3594c9a2a5a9527f2">bumpUpwardPressure</a> and <a href="#a126f33e8085746e4f69b4411b61102dc">recede</a>.</p>

</div>
</div>

### bumpDownwardPressure() {#a2b8b6196a7458b6a84480f03e2f1355d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::bumpDownwardPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the downward impact of a single instruction on current register pressure.</p>


<p>Unlike the advance/recede pressure tracking interface, this does not discover live in/outs.</p>


<p>This is intended for speculative queries. It leaves pressure inconsistent with the current position, so must be restored by the caller.</p>


<p>Declaration at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a797ecc0909ee51516d50dd74698515b5">llvm::RegisterOperands::DeadDefs</a>, <a href="#aeb147ca865dee711c206a23c2fbda878">decreaseRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a2b640124aa4a430ee67d5409120e4deb">llvm::RegisterOperands::Defs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ac9883c9ec5baeee39d4215b9af8e0a70">findUseBetween</a>, <a href="#acb935d3f3c59d7ad1049e01788c65f34">getCurrSlot</a>, <a href="#acba0d5ed53c0ebfa11cc3310e6aef4b1">getLastUsedLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a> and <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acf9cb57c0c3b81e758a2af8aca736842">llvm::RegisterOperands::Uses</a>.</p>


<p>Referenced by <a href="#ac1bfd03ca8fa96ab674c7f7b620dd8a6">getDownwardPressure</a> and <a href="#a972fa38378a3d49a9bb48ca584621438">getMaxDownwardPressureDelta</a>.</p>

</div>
</div>

### bumpUpwardPressure() {#ab0885ecf357ddad3594c9a2a5a9527f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::bumpUpwardPressure (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the upward impact of a single instruction on current register pressure.</p>


<p>Unlike the advance/recede pressure tracking interface, this does not discover live in/outs.</p>


<p>This is intended for speculative queries. It leaves pressure inconsistent with the current position, so must be restored by the caller.</p>


<p>Declaration at line 558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a8affa4b2a934ff08aa04e63253a00126">llvm::RegisterOperands::adjustLaneLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a4cd7dac51234f69ca2c32b7e22f8d27d">bumpDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a74e0a918c9705f23a1e5b66f68cc97e9">llvm::RegisterOperands::collect</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a797ecc0909ee51516d50dd74698515b5">llvm::RegisterOperands::DeadDefs</a>, <a href="#aeb147ca865dee711c206a23c2fbda878">decreaseRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#a2b640124aa4a430ee67d5409120e4deb">llvm::RegisterOperands::Defs</a>, <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acee6dacd4d30da478f3ad67f7fc27142">llvm::RegisterOperands::detectDeadDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a93999c78a867aff95a79a69f287e68c5">getRegLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="#adef3cd5d80fc7eb1bf88f3c9586d6801">increaseRegPressure</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/registeroperands/#acf9cb57c0c3b81e758a2af8aca736842">llvm::RegisterOperands::Uses</a>.</p>


<p>Referenced by <a href="#a41a3118fb6bd46e397256b3c9794b61c">getMaxUpwardPressureDelta</a> and <a href="#ad552b6e557acce957b3bd5a1960a53dd">getUpwardPressure</a>.</p>

</div>
</div>

### discoverLiveIn() {#a1cf29a336b68eceac55ca50d73e19c9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::discoverLiveIn (<a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> Pair)</td>
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

<p>Add Reg to the live in set and increase max pressure.</p>

<p>Declaration at line 550 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Reference <a href="#a60e96ac40c51e2ad7e24f9776fda71d1">discoverLiveInOrOut</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>.</p>

</div>
</div>

### discoverLiveInOrOut() {#a60e96ac40c51e2ad7e24f9776fda71d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::discoverLiveInOrOut (<a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> Pair, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> &gt; &amp; LiveInOrOut)</td>
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



<p>Declaration at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a72988cca7ab2262ef68fdd0c5ae54940">llvm::LaneBitmask::any</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a217ca2f956651626db2bf0fdf48bd82d">increaseSetPressure</a>, <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit/#a77670492e7be5b863b106969e8963a47">llvm::VRegMaskOrUnit::LaneMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit/#a850b5c0b8b36bb79d7bb84f4bb96f91e">llvm::VRegMaskOrUnit::RegUnit</a>.</p>


<p>Referenced by <a href="#a1cf29a336b68eceac55ca50d73e19c9e">discoverLiveIn</a> and <a href="#ae3a5fc111668db50846814135e73973a">discoverLiveOut</a>.</p>

</div>
</div>

### discoverLiveOut() {#ae3a5fc111668db50846814135e73973a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RegPressureTracker::discoverLiveOut (<a href="/web-llvm/docs/api/structs/llvm/vregmaskorunit">VRegMaskOrUnit</a> Pair)</td>
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

<p>Add Reg to the live out set and increase max pressure.</p>

<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Reference <a href="#a60e96ac40c51e2ad7e24f9776fda71d1">discoverLiveInOrOut</a>.</p>


<p>Referenced by <a href="#a126f33e8085746e4f69b4411b61102dc">recede</a>.</p>

</div>
</div>

### getCurrSlot() {#acb935d3f3c59d7ad1049e01788c65f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex RegPressureTracker::getCurrSlot ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> for the first nondebug instruction including or after the current position.</p>

<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a5bacbbd03e9261f7b30dc174f26d680c">llvm::skipDebugInstructionsForward</a>.</p>


<p>Referenced by <a href="#a99487c5b550882cba98d817d47cc3fc0">advance</a>, <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a>, <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a>, <a href="#a204b8f2de53bb48cc63b152400c3fdb6">closeBottom</a> and <a href="#a8759dfc94f9731598942bbbda6280dfe">closeTop</a>.</p>

</div>
</div>

### getLastUsedLanes() {#acba0d5ed53c0ebfa11cc3310e6aef4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask RegPressureTracker::getLastUsedLanes (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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



<p>Declaration at line 564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1246 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#aa94e57689dd16c1c4de909511f1b2ea8">llvm::SlotIndex::getBaseIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a> and <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>.</p>


<p>Referenced by <a href="#a147da0e049b6b53046afe6825447eeaa">advance</a> and <a href="#a2b8b6196a7458b6a84480f03e2f1355d">bumpDownwardPressure</a>.</p>

</div>
</div>

### getLiveLanesAt() {#a9551d47c4a9bc95eec03d02f11dfef3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask RegPressureTracker::getLiveLanesAt (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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



<p>Declaration at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a3714a639930eab71d7202da05ad82990">llvm::LaneBitmask::getAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a400c0b88110521ad1de258a7885d9038">llvm::LiveRange::liveAt</a>.</p>

</div>
</div>

### getLiveThroughAt() {#ad8b14ec0777ac642d3403470e0753533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask RegPressureTracker::getLiveThroughAt (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> RegUnit, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Pos)</td>
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



<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a11bad3e34d11ffb7b0412de6bbd294b3">llvm::SlotIndex::getDeadSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#af22048866afa263f60942281802899e5">getLanesWithProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a9082b6aa4021114645045d9c5628eb26">llvm::LaneBitmask::getNone</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a1cde3a312b39ac23baecfce5fee662f7">llvm::LiveRange::getSegmentContaining</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#a85f7bf79596d84273b5b3b9b490bc2ec">llvm::LiveRange::Segment::start</a>.</p>


<p>Referenced by <a href="#a126f33e8085746e4f69b4411b61102dc">recede</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrPos {#a951c767eaffa84584e349e927a370932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_iterator llvm::RegPressureTracker::CurrPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> pressure corresponds to liveness before this instruction iterator.</p>


<p>It may point to the end of the block or a DebugValue rather than an instruction.</p>


<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### CurrSetPressure {#ae4c83da5c9fd15bb3264cffb2701e4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::RegPressureTracker::CurrSetPressure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pressure map indexed by pressure set <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, not class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>

<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### LIS {#a2584dc4c22eae33b190ca06bc4c60ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveIntervals* llvm::RegPressureTracker::LIS = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### LiveRegs {#a39f88ec4beeb8edde81bc6417528664c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegSet llvm::RegPressureTracker::LiveRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of live registers.</p>

<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### LiveThruPressure {#ade1462fb4a4d1495c81900a157b0d14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;unsigned&gt; llvm::RegPressureTracker::LiveThruPressure</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Live-through pressure.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### MBB {#a9abae53ab9832f1a9b4bad45a91806ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBasicBlock* llvm::RegPressureTracker::MBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We currently only allow pressure tracking within a block.</p>

<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### MF {#a4dee4778d10158e05a68ca73cc0156c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineFunction* llvm::RegPressureTracker::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### MRI {#ad2ba22893f4de8b73273bc832f1b0593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineRegisterInfo* llvm::RegPressureTracker::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### P {#a14611e92832041d5ab0ff4ecee241f16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterPressure&amp; llvm::RegPressureTracker::P</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track the max pressure within the region traversed so far.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### RCI {#a55bea46c11d6e26aedcd74e713b0e2af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterClassInfo* llvm::RegPressureTracker::RCI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### RequireIntervals {#a07c975f8df4fe00450049e2e95da4b7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegPressureTracker::RequireIntervals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run in two modes dependending on whether constructed with <a href="/web-llvm/docs/api/structs/llvm/intervalpressure">IntervalPressure</a> or <a href="/web-llvm/docs/api/structs/llvm/registerpressure">RegisterPressure</a>.</p>


<p>If requireIntervals is false, LIS are ignored.</p>


<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### TrackLaneMasks {#a473dbcaa25e77f7ca125638fe18d2719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegPressureTracker::TrackLaneMasks = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if lanemasks should be tracked.</p>

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### TrackUntiedDefs {#ae059ef7d2d73a1ff8e7f4257810349de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::RegPressureTracker::TrackUntiedDefs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if UntiedDefs will be populated.</p>

<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### TRI {#aae019366b5eb82ee5d10090270e39253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::RegPressureTracker::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

### UntiedDefs {#a8dc60826cad75a1fc9fbbfd0a94a7ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SparseSet&lt;Register, VirtReg2IndexFunctor&gt; llvm::RegPressureTracker::UntiedDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of vreg defs that start a live range.</p>

<p>Definition at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerpressure-h">RegisterPressure.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp">RegisterPressure.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
