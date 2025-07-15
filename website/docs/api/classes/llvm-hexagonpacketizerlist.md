---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hexagonpacketizerlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HexagonPacketizerList` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::HexagonPacketizerList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">Target/Hexagon/HexagonVLIWPacketizer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist">VLIWPacketizerList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd4071843f49d48f53401da3603c0e9">HexagonPacketizerList</a> (MachineFunction &amp;MF, MachineLoopInfo &amp;MLI, AAResults *AA, const MachineBranchProbabilityInfo *MBPI, bool Minimal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5734374d530ee7ee7a3fdda172fc22cd">initPacketizerState</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3867c828f38e2bf9dd517c69c682cc9">ignorePseudoInstruction</a> (const MachineInstr &amp;MI, const MachineBasicBlock *MBB) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4067dba124388f0e4acca8a29fa3c995">isSoloInstruction</a> (const MachineInstr &amp;MI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a> (SUnit *SUI, SUnit *SUJ) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a> (SUnit *SUI, SUnit *SUJ) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a868b649a2ce162e4c94bbc9fcfd5d3ab">foundLSInPacket</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a> (MachineInstr &amp;MI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0917b287f84d46e070dbddb483e4ce94">endPacket</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator MI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2691fcbf8c425f40f56f085b5233783">shouldAddToPacket</a> (const MachineInstr &amp;MI) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa591493a333d880df171a5036eb16449">unpacketizeSoloInstrs</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0950808d354ef314a9d9d37845f2afa1">getmemShufDisabled</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adacef688ed27447aa8a8788811496ed9">setmemShufDisabled</a> (bool val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f967413bf4f246c5eecdabd708ab4a">isCallDependent</a> (const MachineInstr &amp;MI, SDep::Kind DepType, unsigned DepReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd36c93435c58d1b43710d0f328df2d">promoteToDotCur</a> (MachineInstr &amp;MI, SDep::Kind DepType, MachineBasicBlock::iterator &amp;MII, const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284b9287f16ce98d3063620d92f54700">canPromoteToDotCur</a> (const MachineInstr &amp;MI, const SUnit *PacketSU, unsigned DepReg, MachineBasicBlock::iterator &amp;MII, const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8185efd733082b43be2ca1a1b5d977ad">cleanUpDotCur</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d823ecfaee7937234d836e7985fc7b1">promoteToDotNew</a> (MachineInstr &amp;MI, SDep::Kind DepType, MachineBasicBlock::iterator &amp;MII, const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87edaaaaa788f8bc30dfad90aecdb343">canPromoteToDotNew</a> (const MachineInstr &amp;MI, const SUnit *PacketSU, unsigned DepReg, MachineBasicBlock::iterator &amp;MII, const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9085e6f205a2f9604a6458faa9a18d49">canPromoteToNewValue</a> (const MachineInstr &amp;MI, const SUnit *PacketSU, unsigned DepReg, MachineBasicBlock::iterator &amp;MII)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac257b1d3de2b7254c046a5591191e26c">canPromoteToNewValueStore</a> (const MachineInstr &amp;MI, const MachineInstr &amp;PacketMI, unsigned DepReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a368cb9a7fa072861bb90548a42572013">demoteToDotOld</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8fdc79c6fcc0fb997214d040de1063">useCallersSP</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4c903d0a03629b92e4bcc894bbd793">useCalleesSP</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a062ea093e135121a384a1c6c4cd3d96c">updateOffset</a> (SUnit *SUI, SUnit *SUJ)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can update the offset in MI so that MI and MJ can be packetized together. <a href="#a062ea093e135121a384a1c6c4cd3d96c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b034ef532cb4f3326c3744b9625a5b">undoChangedOffset</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Undo the changed offset. <a href="#a72b034ef532cb4f3326c3744b9625a5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0256920aada1bf35dc3c90cbfba10e5d">arePredicatesComplements</a> (MachineInstr &amp;MI1, MachineInstr &amp;MI2)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642903485b484d638fafe7da8142cdd8">restrictingDepExistInPacket</a> (MachineInstr &amp;, unsigned)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85ec932ed39cb089910950893bbe55c">isNewifiable</a> (const MachineInstr &amp;MI, const TargetRegisterClass *NewRC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4248c383940a1f1cc2ecb31722c309ff">isCurifiable</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e0378ea005200a3ee9ee9787dc79df">cannotCoexist</a> (const MachineInstr &amp;MI, const MachineInstr &amp;MJ)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acecb9504ce2bc6d4a2d77996996bfb71">isPromotedToDotNew</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad36ca022c185189ffab3e5b69c97e12b">tryAllocateResourcesForConstExt</a> (bool Reserve)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40822d3425b0713132cccda5f3e0f85">canReserveResourcesForConstExt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf25263c649ddc404f284097fd03df1">reserveResourcesForConstExt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d1857aa86e6720b373f08a74982c93">hasDeadDependence</a> (const MachineInstr &amp;I, const MachineInstr &amp;J)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63671bab1a5a09de954177796404fe02">hasControlDependence</a> (const MachineInstr &amp;I, const MachineInstr &amp;J)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe0ff327925132355807b97771a7a4f5">hasRegMaskDependence</a> (const MachineInstr &amp;I, const MachineInstr &amp;J)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd17a975574e883de8508974c9b6184">hasDualStoreDependence</a> (const MachineInstr &amp;I, const MachineInstr &amp;J)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ef9c94df8b5109e5ad589ea303da44">producesStall</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82b468a911dfb66ebd0e9dfafd6ec6a1">calcStall</a> (const MachineInstr &amp;MI)</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad8119699c8a279b05c6a6ae68f05761">MBPI</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A handle to the branch probability pass. <a href="#aad8119699c8a279b05c6a6ae68f05761">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4011f6cd53120ad9eff880c89c4ee9">MLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a011b218a9038a6ae60279b46037740ac">OldPacketMIs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b18a65d4fe7e7fc171e0b4d0c620b84">PromotedToDotNew</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74dc506c385624a04f84e9d09d4038d5">GlueAllocframeStore</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd1be8f30bb88a06d5b9db63f0d4a696">GlueToNewValueJump</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b5f055dda2cfedbd86125bb90f7805">ChangedOffset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a947782da35c6528ed64bbc71d93962be">Dependence</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9cb0372eb0ae2007f59d8c102b7a14">FoundSequentialDependence</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46bedd0235255a9a2b1c3ad4531e42ee">MemShufDisabled</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c593b6c78f48a1e0ee49f3b92845ec">IgnoreDepMIs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26a9d031b2e7716340759ceac35e3d14">PacketStalls</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12db4e1f9141a620ca7f61363af4c9b8">PacketStallCycles</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d47665b6fff33ad74de2cbf7bde896">PacketHasDuplex</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79db1e9742a6583e6559657b935d5e85">PacketHasSLOT0OnlyInsn</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo">HexagonInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3948a04e2944cb7cc1bf6aae1dca9269">HII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo">HexagonRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7a2858933c82c2385e3254378acc61">HRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5607f0eec5284bb3615b3dba3775a194">Minimal</a></td>
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


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### HexagonPacketizerList() {#a0bd4071843f49d48f53401da3603c0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hexagon Hexagon false HexagonPacketizerList::HexagonPacketizerList (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo">MachineLoopInfo</a> &amp; MLI, <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> * AA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> * MBPI, bool Minimal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a34cd7219145832625cfe1d7b5b873c7d">llvm::VLIWPacketizerList::AA</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a1a4649b5bf16bf1dd02a1edd3a6b44be">llvm::VLIWPacketizerList::addMutation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a21e692502cb75b1488e8b4047000ace6">llvm::HexagonSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#a33ae6b411360f4516d2765ada63756ef">llvm::HexagonSubtarget::getRegisterInfo</a>, <a href="#a0bd4071843f49d48f53401da3603c0e9">HexagonPacketizerList</a>, <a href="#aad8119699c8a279b05c6a6ae68f05761">MBPI</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a>, <a href="#a3e4011f6cd53120ad9eff880c89c4ee9">MLI</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a1535a24a0c1b6049bba8cce276f8033f">llvm::VLIWPacketizerList::VLIWPacketizerList</a>.</p>


<p>Referenced by <a href="#a0bd4071843f49d48f53401da3603c0e9">HexagonPacketizerList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToPacket() {#aec7e812b238864a5d4ddc2c6b2548c74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator HexagonPacketizerList::addToPacket (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1710 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a82b468a911dfb66ebd0e9dfafd6ec6a1">calcStall</a>, <a href="#ab40822d3425b0713132cccda5f3e0f85">canReserveResourcesForConstExt</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="#a368cb9a7fa072861bb90548a42572013">demoteToDotOld</a>, <a href="#a0917b287f84d46e070dbddb483e4ce94">endPacket</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a65ef9c94df8b5109e5ad589ea303da44">producesStall</a>, <a href="#adcf25263c649ddc404f284097fd03df1">reserveResourcesForConstExt</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#aa563675151ea61dfc14e8dd078327bc9">llvm::VLIWPacketizerList::ResourceTracker</a>, <a href="#ad36ca022c185189ffab3e5b69c97e12b">tryAllocateResourcesForConstExt</a> and <a href="#a2c4c903d0a03629b92e4bcc894bbd793">useCalleesSP</a>.</p>

</div>
</div>

### endPacket() {#a0917b287f84d46e070dbddb483e4ce94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::endPacket (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1789 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="#a868b649a2ce162e4c94bbc9fcfd5d3ab">foundLSInPacket</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator/#a897c4661275324674e38c41a52e7fc88">llvm::MachineInstrBundleIterator&lt; Ty, IsReverse &gt;::getInstrIterator</a>, <a href="#a0950808d354ef314a9d9d37845f2afa1">getmemShufDisabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#aa563675151ea61dfc14e8dd078327bc9">llvm::VLIWPacketizerList::ResourceTracker</a>, <a href="#adacef688ed27447aa8a8788811496ed9">setmemShufDisabled</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3beda524b0772ca36035db4399a6a571">llvm::utohexstr</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a>.</p>

</div>
</div>

### foundLSInPacket() {#a868b649a2ce162e4c94bbc9fcfd5d3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::foundLSInPacket ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1690 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>.</p>


<p>Referenced by <a href="#a0917b287f84d46e070dbddb483e4ce94">endPacket</a>.</p>

</div>
</div>

### ignorePseudoInstruction() {#aa3867c828f38e2bf9dd517c69c682cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::ignorePseudoInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1044 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a03a564c2840cb8d27314596549fc04b8">llvm::MCInstrDesc::getSchedClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#aa563675151ea61dfc14e8dd078327bc9">llvm::VLIWPacketizerList::ResourceTracker</a>.</p>

</div>
</div>

### initPacketizerState() {#a5734374d530ee7ee7a3fdda172fc22cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::initPacketizerState ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1034 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>.</p>

</div>
</div>

### isLegalToPacketizeTogether() {#a2526f4f46289ec5bfb0201a6963b6a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::isLegalToPacketizeTogether (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUI, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUJ)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1325 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a5a49db9f3f84ee0258f9db321f1c7f9f">llvm::VLIWPacketizerList::alias</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="#a0256920aada1bf35dc3c90cbfba10e5d">arePredicatesComplements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a36e0378ea005200a3ee9ee9787dc79df">cannotCoexist</a>, <a href="#a284b9287f16ce98d3063620d92f54700">canPromoteToDotCur</a>, <a href="#a87edaaaaa788f8bc30dfad90aecdb343">canPromoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#a63671bab1a5a09de954177796404fe02">hasControlDependence</a>, <a href="#af4d1857aa86e6720b373f08a74982c93">hasDeadDependence</a>, <a href="#a7bd17a975574e883de8508974c9b6184">hasDualStoreDependence</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aabc3917d917c6247778c88107945d13b">llvm::MachineInstr::hasOrderedMemoryRef</a>, <a href="#afe0ff327925132355807b97771a7a4f5">hasRegMaskDependence</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonsubtarget/#ad61a073a966a5810f636cfc5df331b0d">llvm::HexagonSubtarget::hasV65Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5891cdb51072f67e65f7ebd9be1205e7">llvm::MachineInstr::isBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>, <a href="#a10f967413bf4f246c5eecdabd708ab4a">isCallDependent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a0a2728add68625c42d7e94c9339c3109">isDirectJump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a311b8c04ec795da16c375d7a4b422bd2">isRegDependence</a>, <a href="#a4067dba124388f0e4acca8a29fa3c995">isSoloInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a65e96694f0d2eef93a9653beba7d12dc">llvm::SUnit::isSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a66e91c5407ade0326e5dbd87e986e648">llvm::MachineInstr::modifiesRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a67742b87d83369cad814985a4afc83d0">llvm::SDep::Order</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732a011a1d87822a7f70efee9e430a7ccc36">llvm::SDep::Output</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a8f23099d228fd1361516e2008f9a2fdd">PacketizeVolatiles</a>, <a href="#a1bd36c93435c58d1b43710d0f328df2d">promoteToDotCur</a>, <a href="#a1d823ecfaee7937234d836e7985fc7b1">promoteToDotNew</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2380c209ae5339835b5e6ea6d5c197ad">llvm::MachineInstr::readsRegister</a>, <a href="#adacef688ed27447aa8a8788811496ed9">setmemShufDisabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a8c2b74d69e8b99aa43762e856cd5280c">Slot1Store</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a> and <a href="#abf8fdc79c6fcc0fb997214d040de1063">useCallersSP</a>.</p>

</div>
</div>

### isLegalToPruneDependencies() {#a49f30830f4e853ee33ad7b021d0f5403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::isLegalToPruneDependencies (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUI, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUJ)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a36e0378ea005200a3ee9ee9787dc79df">cannotCoexist</a>, <a href="#a8185efd733082b43be2ca1a1b5d977ad">cleanUpDotCur</a>, <a href="#a368cb9a7fa072861bb90548a42572013">demoteToDotOld</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, <a href="#a72b034ef532cb4f3326c3744b9625a5b">undoChangedOffset</a>, <a href="#a062ea093e135121a384a1c6c4cd3d96c">updateOffset</a> and <a href="#a2c4c903d0a03629b92e4bcc894bbd793">useCalleesSP</a>.</p>

</div>
</div>

### isSoloInstruction() {#a4067dba124388f0e4acca8a29fa3c995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::isSoloInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1066 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aedb49a59ba27d6eae99eadbf090a5171">isSchedBarrier</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#a9a6593913392c38d82820cceb4a51f05">ScheduleInlineAsm</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### shouldAddToPacket() {#ab2691fcbf8c425f40f56f085b5233783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::shouldAddToPacket (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a65ef9c94df8b5109e5ad589ea303da44">producesStall</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#aa563675151ea61dfc14e8dd078327bc9">llvm::VLIWPacketizerList::ResourceTracker</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9117508fb00fda14207e7f968389544c">llvm::MachineInstr::setDesc</a>.</p>

</div>
</div>

### unpacketizeSoloInstrs() {#aa591493a333d880df171a5036eb16449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::unpacketizeSoloInstrs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aa2eaa868ed1dfcc89946d7b7fc4d2149">hasWriteToReadDep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a263c68370ee4203b80d388fd7b89ebb5">moveInstrOut</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### arePredicatesComplements() {#a0256920aada1bf35dc3c90cbfba10e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::arePredicatesComplements (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI1, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI2)</td>
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



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a68cebe53cac420d7b1dcde0a79304cc0">getPredicatedRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a5fe53637e6201b2fd01d8a0a954c4a6a">getPredicateSense</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a65e96694f0d2eef93a9653beba7d12dc">llvm::SUnit::isSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a73fbb834524be9f7106e907bff83cf06">llvm::VLIWPacketizerList::MIToSUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a8d60d6c6e0f8d29d2ee342209c93a36ea1418e0de5990064da570cea12cf7059b">PK_Unknown</a>, <a href="#a642903485b484d638fafe7da8142cdd8">restrictingDepExistInPacket</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### calcStall() {#a82b468a911dfb66ebd0e9dfafd6ec6a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int HexagonPacketizerList::calcStall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1879 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a73fbb834524be9f7106e907bff83cf06">llvm::VLIWPacketizerList::MIToSUnit</a>, <a href="#a3e4011f6cd53120ad9eff880c89c4ee9">MLI</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a> and <a href="#a65ef9c94df8b5109e5ad589ea303da44">producesStall</a>.</p>

</div>
</div>

### cannotCoexist() {#a36e0378ea005200a3ee9ee9787dc79df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::cannotCoexist (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MJ)</td>
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



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a006a3e1788b7d4a381385cd00ed19508">cannotCoexistAsymm</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a> and <a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a>.</p>

</div>
</div>

### canPromoteToDotCur() {#a284b9287f16ce98d3063620d92f54700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::canPromoteToDotCur (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * PacketSU, unsigned DepReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 407 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a4b743093219cfca13b1ec2cb58903fba">llvm::MachineInstr::isInlineAsm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### canPromoteToDotNew() {#a87edaaaaa788f8bc30dfad90aecdb343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::canPromoteToDotNew (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * PacketSU, unsigned DepReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="#a9085e6f205a2f9604a6458faa9a18d49">canPromoteToNewValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a5c526ff882b00cc421929bdae63aeda8">DisableVecDblNVStores</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a120ccebe70e1b0ddf72fc776229d0025">llvm::MachineInstr::isImplicitDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#ae27efac50f5a56e780768d08f1101fb9">isImplicitDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a4b743093219cfca13b1ec2cb58903fba">llvm::MachineInstr::isInlineAsm</a>, <a href="#af85ec932ed39cb089910950893bbe55c">isNewifiable</a>, <a href="#aad8119699c8a279b05c6a6ae68f05761">MBPI</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#aa563675151ea61dfc14e8dd078327bc9">llvm::VLIWPacketizerList::ResourceTracker</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### canPromoteToNewValue() {#a9085e6f205a2f9604a6458faa9a18d49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::canPromoteToNewValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * PacketSU, unsigned DepReg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MII)</td>
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



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 820 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="#ac257b1d3de2b7254c046a5591191e26c">canPromoteToNewValueStore</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a87edaaaaa788f8bc30dfad90aecdb343">canPromoteToDotNew</a>.</p>

</div>
</div>

### canPromoteToNewValueStore() {#ac257b1d3de2b7254c046a5591191e26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::canPromoteToNewValueStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; PacketMI, unsigned DepReg)</td>
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



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#ad8f1a441511819e7981b34cbe085ceeb">getAbsSetOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#add65febd7d533102fe2c2c2a7e244751">getPostIncrementOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a5fe53637e6201b2fd01d8a0a954c4a6a">getPredicateSense</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a459ea26e1f92eab1e5645dafc995a2de">getStoreValueOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#ab1fa3dd0780832053b30f808e8893aeb">isLoadAbsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a682028ac4a06c9e3550fa8e6e1909fa9">llvm::MachineInstr::mayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a73fbb834524be9f7106e907bff83cf06">llvm::VLIWPacketizerList::MIToSUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a66e91c5407ade0326e5dbd87e986e648">llvm::MachineInstr::modifiesRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>.</p>


<p>Referenced by <a href="#a9085e6f205a2f9604a6458faa9a18d49">canPromoteToNewValue</a>.</p>

</div>
</div>

### canReserveResourcesForConstExt() {#ab40822d3425b0713132cccda5f3e0f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::canReserveResourcesForConstExt ()</td>
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



<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>Reference <a href="#ad36ca022c185189ffab3e5b69c97e12b">tryAllocateResourcesForConstExt</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a>.</p>

</div>
</div>

### cleanUpDotCur() {#a8185efd733082b43be2ca1a1b5d977ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::cleanUpDotCur ()</td>
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



<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a>.</p>

</div>
</div>

### demoteToDotOld() {#a368cb9a7fa072861bb90548a42572013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::demoteToDotOld (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a> and <a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a>.</p>

</div>
</div>

### getmemShufDisabled() {#a0950808d354ef314a9d9d37845f2afa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::getmemShufDisabled ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>


<p>Referenced by <a href="#a0917b287f84d46e070dbddb483e4ce94">endPacket</a>.</p>

</div>
</div>

### hasControlDependence() {#a63671bab1a5a09de954177796404fe02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::hasControlDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; J)</td>
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



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#aa38ce9de80252e6af533d4544dde77b7">doesModifyCalleeSavedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a2dbc79cfed570a9127d2853385162bdf">llvm::MachineInstr::isBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5891cdb51072f67e65f7ebd9be1205e7">llvm::MachineInstr::isBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#a4e265d5e49cf5c931e58c8c963e0031b">isControlFlow</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### hasDeadDependence() {#af4d1857aa86e6720b373f08a74982c93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::hasDeadDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; J)</td>
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



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### hasDualStoreDependence() {#a7bd17a975574e883de8508974c9b6184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::hasDualStoreDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; J)</td>
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



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp/#af1461876a909bd02a6c81c6d4f0a1fc3">isSystemInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab96f3235c18e659758517d0532d606c9">llvm::MachineInstr::mayStore</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### hasRegMaskDependence() {#afe0ff327925132355807b97771a7a4f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::hasRegMaskDependence (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; J)</td>
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



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1270 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a30e7d619f3195fd890116da8b3ed6bab">llvm::MachineInstr::isCall</a> and <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### isCallDependent() {#a10f967413bf4f246c5eecdabd708ab4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::isCallDependent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732">SDep::Kind</a> DepType, unsigned DepReg)</td>
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



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### isCurifiable() {#a4248c383940a1f1cc2ecb31722c309ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::isCurifiable (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isNewifiable() {#af85ec932ed39cb089910950893bbe55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::isNewifiable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * NewRC)</td>
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



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a87edaaaaa788f8bc30dfad90aecdb343">canPromoteToDotNew</a>.</p>

</div>
</div>

### isPromotedToDotNew() {#acecb9504ce2bc6d4a2d77996996bfb71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::isPromotedToDotNew ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### producesStall() {#a65ef9c94df8b5109e5ad589ea303da44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::producesStall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 1940 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="#a82b468a911dfb66ebd0e9dfafd6ec6a1">calcStall</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06a2d68d32ff95cd10b4899c2823ec28e97">llvm::Latency</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a> and <a href="#ab2691fcbf8c425f40f56f085b5233783">shouldAddToPacket</a>.</p>

</div>
</div>

### promoteToDotCur() {#a1bd36c93435c58d1b43710d0f328df2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::promoteToDotCur (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732">SDep::Kind</a> DepType, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### promoteToDotNew() {#a1d823ecfaee7937234d836e7985fc7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::promoteToDotNew (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732">SDep::Kind</a> DepType, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; MII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
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



<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="#aad8119699c8a279b05c6a6ae68f05761">MBPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### reserveResourcesForConstExt() {#adcf25263c649ddc404f284097fd03df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::reserveResourcesForConstExt ()</td>
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



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ad36ca022c185189ffab3e5b69c97e12b">tryAllocateResourcesForConstExt</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a>.</p>

</div>
</div>

### restrictingDepExistInPacket() {#a642903485b484d638fafe7da8142cdd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::restrictingDepExistInPacket (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned DepReg)</td>
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



<p>Declaration at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 920 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a6ce4208a9adff0d4c41486339da72880">llvm::VLIWPacketizerList::CurrentPacketMIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a65e96694f0d2eef93a9653beba7d12dc">llvm::SUnit::isSucc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a73fbb834524be9f7106e907bff83cf06">llvm::VLIWPacketizerList::MIToSUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab4a86c51e6b126c9c6ef58dbb574431">llvm::SUnit::Succs</a>.</p>


<p>Referenced by <a href="#a0256920aada1bf35dc3c90cbfba10e5d">arePredicatesComplements</a>.</p>

</div>
</div>

### setmemShufDisabled() {#adacef688ed27447aa8a8788811496ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HexagonPacketizerList::setmemShufDisabled (bool val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>


<p>Referenced by <a href="#a0917b287f84d46e070dbddb483e4ce94">endPacket</a> and <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

### tryAllocateResourcesForConstExt() {#ad36ca022c185189ffab3e5b69c97e12b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::tryAllocateResourcesForConstExt (bool Reserve)</td>
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



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#aa563675151ea61dfc14e8dd078327bc9">llvm::VLIWPacketizerList::ResourceTracker</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a>, <a href="#ab40822d3425b0713132cccda5f3e0f85">canReserveResourcesForConstExt</a> and <a href="#adcf25263c649ddc404f284097fd03df1">reserveResourcesForConstExt</a>.</p>

</div>
</div>

### undoChangedOffset() {#a72b034ef532cb4f3326c3744b9625a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::undoChangedOffset (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Undo the changed offset.</p>


<p>This is needed if the instruction cannot be added to the current packet due to a different instruction.</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h/#a0b0cd724f4b7f8589a602b17d6caa1fb">OP</a>.</p>


<p>Referenced by <a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a>.</p>

</div>
</div>

### updateOffset() {#a062ea093e135121a384a1c6c4cd3d96c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::updateOffset (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUI, <a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SUJ)</td>
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

<p>Return true if we can update the offset in MI so that MI and MJ can be packetized together.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732abe9561936346ab5c5e22fe544994b06e">llvm::SDep::Anti</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#a07333f8ba53e0454b7ec6365860c0732af91df2221290eaa1a368403ffad49a26">llvm::SDep::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/sunit/#ae2b43854b542de66eec6475adc48f56c">llvm::SUnit::Preds</a>.</p>


<p>Referenced by <a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a>.</p>

</div>
</div>

### useCalleesSP() {#a2c4c903d0a03629b92e4bcc894bbd793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HexagonPacketizerList::useCalleesSP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a39298692b00c8dc4bb83650c5414b83b">HEXAGON_LRFP_SIZE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aec7e812b238864a5d4ddc2c6b2548c74">addToPacket</a> and <a href="#a49f30830f4e853ee33ad7b021d0f5403">isLegalToPruneDependencies</a>.</p>

</div>
</div>

### useCallersSP() {#abf8fdc79c6fcc0fb997214d040de1063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HexagonPacketizerList::useCallersSP (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>, definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-h/#a39298692b00c8dc4bb83650c5414b83b">HEXAGON_LRFP_SIZE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/vliwpacketizerlist/#a12b3d85290b815a7b870ea1b841d4288">llvm::VLIWPacketizerList::MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a2526f4f46289ec5bfb0201a6963b6a1b">isLegalToPacketizeTogether</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### MBPI {#aad8119699c8a279b05c6a6ae68f05761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* llvm::HexagonPacketizerList::MBPI</td>
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

<p>A handle to the branch probability pass.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>


<p>Referenced by <a href="#a87edaaaaa788f8bc30dfad90aecdb343">canPromoteToDotNew</a>, <a href="#a0bd4071843f49d48f53401da3603c0e9">HexagonPacketizerList</a> and <a href="#a1d823ecfaee7937234d836e7985fc7b1">promoteToDotNew</a>.</p>

</div>
</div>

### MLI {#a3e4011f6cd53120ad9eff880c89c4ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineLoopInfo* llvm::HexagonPacketizerList::MLI</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>


<p>Referenced by <a href="#a82b468a911dfb66ebd0e9dfafd6ec6a1">calcStall</a> and <a href="#a0bd4071843f49d48f53401da3603c0e9">HexagonPacketizerList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ChangedOffset {#a63b5f055dda2cfedbd86125bb90f7805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::HexagonPacketizerList::ChangedOffset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### Dependence {#a947782da35c6528ed64bbc71d93962be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::Dependence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### FoundSequentialDependence {#a9a9cb0372eb0ae2007f59d8c102b7a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::FoundSequentialDependence</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### GlueAllocframeStore {#a74dc506c385624a04f84e9d09d4038d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::GlueAllocframeStore</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### GlueToNewValueJump {#abd1be8f30bb88a06d5b9db63f0d4a696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::GlueToNewValueJump</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### HII {#a3948a04e2944cb7cc1bf6aae1dca9269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonInstrInfo* llvm::HexagonPacketizerList::HII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### HRI {#abb7a2858933c82c2385e3254378acc61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HexagonRegisterInfo* llvm::HexagonPacketizerList::HRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### IgnoreDepMIs {#aa3c593b6c78f48a1e0ee49f3b92845ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr*&gt; llvm::HexagonPacketizerList::IgnoreDepMIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### MemShufDisabled {#a46bedd0235255a9a2b1c3ad4531e42ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::MemShufDisabled = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### Minimal {#a5607f0eec5284bb3615b3dba3775a194}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::HexagonPacketizerList::Minimal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### OldPacketMIs {#a011b218a9038a6ae60279b46037740ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr *&gt; llvm::HexagonPacketizerList::OldPacketMIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### PacketHasDuplex {#a73d47665b6fff33ad74de2cbf7bde896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::PacketHasDuplex = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### PacketHasSLOT0OnlyInsn {#a79db1e9742a6583e6559657b935d5e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::PacketHasSLOT0OnlyInsn = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### PacketStallCycles {#a12db4e1f9141a620ca7f61363af4c9b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int llvm::HexagonPacketizerList::PacketStallCycles = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### PacketStalls {#a26a9d031b2e7716340759ceac35e3d14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::PacketStalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

### PromotedToDotNew {#a1b18a65d4fe7e7fc171e0b4d0c620b84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::HexagonPacketizerList::PromotedToDotNew</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-cpp">HexagonVLIWPacketizer.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvliwpacketizer-h">HexagonVLIWPacketizer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
