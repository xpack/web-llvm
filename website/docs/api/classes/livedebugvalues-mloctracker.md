---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/livedebugvalues/mloctracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MLocTracker` Class Reference

<p>Tracker for what values are in machine locations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LiveDebugValues::MLocTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">CodeGen/LiveDebugValues/InstrRefBasedImpl.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b01eec8f769336a32dacc18974c2c9">LocToValueType</a> = <a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidxtoindexfunctor">LocIdxToIndexFunctor</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a> type, mapping from <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> to <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>. <a href="#ab0b01eec8f769336a32dacc18974c2c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::pair&lt; unsigned short, unsigned short &gt; <a href="#a758eab2c8cea4d5486874624dba188b4">StackSlotPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pair for describing a position within a stack slot – first the size in bits, then the offset. <a href="#a758eab2c8cea4d5486874624dba188b4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a> (MachineFunction &amp;MF, const TargetInstrInfo &amp;TII, const TargetRegisterInfo &amp;TRI, const TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for a <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>. <a href="#a2a28f143303b39650c069b1ce0925287">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e7aca955e2c1f76d2f20f4475fe716d">getLocID</a> (SpillLocationNo Spill, unsigned SpillSubReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for a spill position. <a href="#a1e7aca955e2c1f76d2f20f4475fe716d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223c8809c8643ad30bae41da7699b608">getLocID</a> (SpillLocationNo Spill, StackSlotPos Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Produce location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for a spill position. <a href="#a223c8809c8643ad30bae41da7699b608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c44cbd0dca6d3e9736ce4f240af2e25">getSpillIDWithIdx</a> (SpillLocationNo Spill, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a spill number, and a slot within the spill, calculate the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for that location. <a href="#a1c44cbd0dca6d3e9736ce4f240af2e25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63cf4d79a939e187701ac667cb07f5d7">locIDToSpill</a> (unsigned ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the spill number that a location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> corresponds to. <a href="#a63cf4d79a939e187701ac667cb07f5d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a758eab2c8cea4d5486874624dba188b4">StackSlotPos</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a> (unsigned ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the spill-slot size/offs that a location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> corresponds to. <a href="#af39200a4599a5fc61a89ca83ce64598a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b9880cdbbdc53b8e5446db5dede09b">getNumLocs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc84cf80598821cf657ee831fce024bc">setMPhis</a> (unsigned NewCurBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset all locations to contain a PHI value at the designated block. <a href="#abc84cf80598821cf657ee831fce024bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f6a2afd0fe02e3fcfcc5d75d186c21b">loadFromArray</a> (ValueTable &amp;Locs, unsigned NewCurBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load values for each location from array of ValueIDNums. <a href="#a0f6a2afd0fe02e3fcfcc5d75d186c21b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66a31574ce11e5d8dc78ed9a845305c2">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wipe any un-necessary location records after traversing a block. <a href="#a66a31574ce11e5d8dc78ed9a845305c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear all data. <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed8c7355168afd27f9f47f505026c54">setMLoc</a> (LocIdx L, ValueIDNum Num)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a locaiton to a certain value. <a href="#a8ed8c7355168afd27f9f47f505026c54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8ae8456399284b13679782065ee5dfc">readMLoc</a> (LocIdx L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the value of a particular location. <a href="#ab8ae8456399284b13679782065ee5dfc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c12fcc919645ec5ae40a9763d756ba">trackRegister</a> (unsigned ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> for an untracked register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>. <a href="#ae0c12fcc919645ec5ae40a9763d756ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a> (unsigned ID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0975fbd8e22dcc611900504cbe982610">isRegisterTracked</a> (Register R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is register R currently tracked by <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a>? <a href="#a0975fbd8e22dcc611900504cbe982610">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b28d7abd903bca80aebdd56d893e8b">defReg</a> (Register R, unsigned BB, unsigned Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a definition of the specified register at the given block / inst. <a href="#ad4b28d7abd903bca80aebdd56d893e8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f3e7fca669ee92300565d5e78098311">setReg</a> (Register R, ValueIDNum ValueID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a register to a value number. <a href="#a5f3e7fca669ee92300565d5e78098311">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5a8547e6be549b193c89c9202889df">readReg</a> (Register R)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c013a9da07953941f1e4e464d75db00">wipeRegister</a> (Register R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset a register value to zero / empty. <a href="#a8c013a9da07953941f1e4e464d75db00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88df5839a1471739fba42290c3a8279a">getRegMLoc</a> (Register R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> of an existing register. <a href="#a88df5839a1471739fba42290c3a8279a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a> (const MachineOperand *MO, unsigned CurBB, unsigned InstID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a RegMask operand being executed. <a href="#a73d25ebef02d1312bd901c694d7321ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a> (SpillLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> for <a href="/web-llvm/docs/api/structs/livedebugvalues/spillloc">SpillLoc</a> <span class="doxyComputerOutput">L</span>, creating a new one if it's not tracked. <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd78a5b47f366715a6871891a6ad5fb0">getSpillMLoc</a> (unsigned SpillID)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87fc8660fb193f626f9e9a6f0244108e">isSpill</a> (LocIdx Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if Idx is a spill machine location. <a href="#a87fc8660fb193f626f9e9a6f0244108e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a> (LocIdx L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How large is this location (aka, how wide is a value defined there?). <a href="#a00b889b10d5eaeb7be44d959e67263c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/mlociterator">MLocIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac227f75996b7c2ab468a3faa25711c">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/mlociterator">MLocIterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a303e01bf517a6275123cfb03d0703f08">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/mlociterator">MLocIterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217987fff459e088b64f179204e120f1">locations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a range over all locations currently tracked. <a href="#a217987fff459e088b64f179204e120f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a> (LocIdx Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d5f445ba9f76ce9d0a11bc11e8e1a9">IDAsString</a> (const ValueIDNum &amp;Num) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad60ba0b6dcb54a7fe37863ceb0165626">dump</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0c9cdac0acbe1745277e6e9544aa575">dump_mloc_map</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a> (const SmallVectorImpl&lt; ResolvedDbgOp &gt; &amp;DbgOps, const DebugVariable &amp;Var, const DILocation *DILoc, const DbgValueProperties &amp;Properties)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DBG_VALUE based on debug operands <span class="doxyComputerOutput">DbgOps</span>. <a href="#a88fd52c520cef6a03af97c37c308ae78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a29742ce2fd47f4b4769dfe5a44f9e">MF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcfe28f8a994ea7a5fff050f1c09fd2">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3870dfac7df420149911b3e81c6c155a">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ceb7dab8f0063eec8dff6df6d2a3eda">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab0b01eec8f769336a32dacc18974c2c9">LocToValueType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of LocIdxes to the ValueIDNums that they store. <a href="#a91fd5d450920e56cbde71ab8708fbab9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>"Map" of machine location IDs (i.e., raw register or spill number) to the <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> key / number for that location. <a href="#a9b700e192036873e9756f231c9213a34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidxtoindexfunctor">LocIdxToIndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/inverse">Inverse</a> map of LocIDToLocIdx. <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2773f3976918a270bac316739f66ffd5">SPAliases</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When clobbering register masks, we chose to not believe the machine model and don't clobber SP. <a href="#a2773f3976918a270bac316739f66ffd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/uniquevector">UniqueVector</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/spillloc">SpillLoc</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8795e147779aed8a5d0af6783babaa0">SpillLocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique-ification of spill. <a href="#ab8795e147779aed8a5d0af6783babaa0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2017e35cd152cf2e3885ea8ed8e3d8f5">CurBB</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cached local copy of the number of registers the target has. <a href="#a3d106e52bda90530904b18edf24f2286">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of slot indexes the target has – distinct segments of a stack slot that can take on the value of a subregister, when a super-register is written to the stack. <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, unsigned &gt;, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab115d98ec0127b8b019aae3e5e296efc">Masks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of register mask operands that have been observed. <a href="#ab115d98ec0127b8b019aae3e5e296efc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="#a758eab2c8cea4d5486874624dba188b4">StackSlotPos</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afcbfb84f0bb09c726e9a777d9f01e7">StackSlotIdxes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from a size/offset pair describing a position in a stack slot, to a numeric identifier for that position. <a href="#a5afcbfb84f0bb09c726e9a777d9f01e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="#a758eab2c8cea4d5486874624dba188b4">StackSlotPos</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa795efcfec488fc9683b69b1f9a4d3">StackIdxesToPos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/inverse">Inverse</a> of StackSlotIdxes. <a href="#a6fa795efcfec488fc9683b69b1f9a4d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Tracker for what values are in machine locations.</p>


<p>Listens to the Things being Done by various instructions, and maintains a table of what machine locations have what values (as defined by a <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>).</p>


<p>There are potentially a much larger number of machine locations on the target machine than the actual working-set size of the function. On x86 for example, we're extremely unlikely to want to track values through control or debug registers. To avoid doing so, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> has several layers of indirection going on, described below, to avoid unnecessarily tracking any location.</p>


<p>Here's a sort of diagram of the indexes, read from the bottom up:</p>



<pre><code>      Size on stack   Offset on stack
            \              /
     Stack Idx (Where in slot is this?)
                    /
                   /
</code></pre>


<p>Slot Num (stack.0) / FrameIdx =&gt; SpillNum / \ / SpillID (int) <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> number (int) \ / LocationID =&gt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> | <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> =&gt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a></p>


<p>The aim here is that the <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> =&gt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> vector is just an array of values in numbered locations, so that later analyses can ignore whether the location is a register or otherwise. To map a register / spill location to a <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a>, you have to use the (sparse) LocationID =&gt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> map. And to build a LocationID for a stack slot, you need to combine identifiers for which stack slot it is and where within that slot is being described.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/register">Register</a> mask operands cause trouble by technically defining every register; various hacks are used to avoid tracking registers that are never read and only written by regmasks.</p>


<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LocToValueType {#ab0b01eec8f769336a32dacc18974c2c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LiveDebugValues::MLocTracker::LocToValueType =  IndexedMap&lt;ValueIDNum, LocIdxToIndexFunctor&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a> type, mapping from <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> to <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>.</p>

<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### StackSlotPos {#a758eab2c8cea4d5486874624dba188b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::pair&lt;unsigned short, unsigned short&gt; LiveDebugValues::MLocTracker::StackSlotPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pair for describing a position within a stack slot – first the size in bits, then the offset.</p>

<p>Definition at line 748 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MLocTracker() {#ae118b50388837cac4d807896b91f111e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLocTracker::MLocTracker (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 791 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1020 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a8567f7c20eae6b2f5beabaa440df1097">LiveDebugValues::LocIdx::MakeIllegalLoc</a>, <a href="#ae1a29742ce2fd47f4b4769dfe5a44f9e">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h/#a09551aadf1cfb2c7160bcd6314b9f748">NUM_LOC_BITS</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>, <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a>, <a href="#a66a31574ce11e5d8dc78ed9a845305c2">reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a2773f3976918a270bac316739f66ffd5">SPAliases</a>, <a href="#a6fa795efcfec488fc9683b69b1f9a4d3">StackIdxesToPos</a>, <a href="#a5afcbfb84f0bb09c726e9a777d9f01e7">StackSlotIdxes</a>, <a href="#a7bcfe28f8a994ea7a5fff050f1c09fd2">TII</a>, <a href="#a2ceb7dab8f0063eec8dff6df6d2a3eda">TLI</a> and <a href="#a3870dfac7df420149911b3e81c6c155a">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a3ac227f75996b7c2ab468a3faa25711c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLocIterator LiveDebugValues::MLocTracker::begin ()</td>
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



<p>Definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>.</p>


<p>Referenced by <a href="#a217987fff459e088b64f179204e120f1">locations</a>.</p>

</div>
</div>

### clear() {#aaef75d1e01cf50cbf889096d2a6f3f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::clear ()</td>
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

<p>Clear all data.</p>


<p>Destroys the LocID &lt;=&gt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> map, which makes most of the information in this pass uninterpretable.</p>


<p>Definition at line 878 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a8567f7c20eae6b2f5beabaa440df1097">LiveDebugValues::LocIdx::MakeIllegalLoc</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>, <a href="#a66a31574ce11e5d8dc78ed9a845305c2">reset</a>, <a href="#ab8795e147779aed8a5d0af6783babaa0">SpillLocs</a>, <a href="#a6fa795efcfec488fc9683b69b1f9a4d3">StackIdxesToPos</a> and <a href="#a5afcbfb84f0bb09c726e9a777d9f01e7">StackSlotIdxes</a>.</p>

</div>
</div>

### defReg() {#ad4b28d7abd903bca80aebdd56d893e8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::defReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, unsigned BB, unsigned Inst)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a definition of the specified register at the given block / inst.</p>


<p>This doesn't take a <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>, because the definition and its location are synonymous.</p>


<p>Definition at line 924 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a> and <a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a>.</p>


<p>Referenced by <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### dump() {#ad60ba0b6dcb54a7fe37863ceb0165626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MLocTracker::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a217987fff459e088b64f179204e120f1">locations</a> and <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a>.</p>

</div>
</div>

### dump\_mloc\_map() {#af0c9cdac0acbe1745277e6e9544aa575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MLocTracker::dump_mloc_map ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1013 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>, <a href="#a217987fff459e088b64f179204e120f1">locations</a> and <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a>.</p>

</div>
</div>

### emitLoc() {#a88fd52c520cef6a03af97c37c308ae78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder MLocTracker::emitLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/resolveddbgop">ResolvedDbgOp</a> &gt; &amp; DbgOps, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp; Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DILoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Properties)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a DBG_VALUE based on debug operands <span class="doxyComputerOutput">DbgOps</span>.</p>


<p>Qualify it with the information in \pProperties, for variable Var. Don't insert it anywhere, just return the builder for it.</p>


<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5f48305fa7d23161515c94bca7c2beb6">llvm::DIExpression::appendOpsToArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::SmallVectorImpl&lt; T &gt;::assign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#a87d598e34086fb45a3a64638bdc6097e">LiveDebugValues::DbgValueProperties::DIExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#adcfb72c9275acde495226af4ad12e180">llvm::DebugVariable::getFragment</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#ae1a6cd7bbbd214de5c1990def99b1c57">LiveDebugValues::DbgValueProperties::getLocationOpCount</a>, <a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/divariable/#a6b5977deeb9f99e156685e190de78403">llvm::DIVariable::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#af2ca096ab72c055f6c2c7e3ffbe5d6bf">llvm::DebugVariable::getVariable</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno/#a2e309fd3b79f17ba6213f7eb9d637329">LiveDebugValues::SpillLocationNo::id</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#a7f88fbb422e5e0d5c0e227b3df0bd8a8">LiveDebugValues::DbgValueProperties::Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a7926734793677673e68d8cff410552ec">llvm::DIExpression::isComplex</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a40cd3c3332ecc579f7a92924714d6d5c">llvm::DIExpression::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac9a4fe1aa8e698aa8cd6a24751a80d91">llvm::DIExpression::isSingleLocationExpression</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#aebaf15eb5116df110c1de27c5c8901a2">LiveDebugValues::DbgValueProperties::IsVariadic</a>, <a href="#a63cf4d79a939e187701ac667cb07f5d7">locIDToSpill</a>, <a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#ae1a29742ce2fd47f4b4769dfe5a44f9e">MF</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#ab8795e147779aed8a5d0af6783babaa0">SpillLocs</a>, <a href="#a7bcfe28f8a994ea7a5fff050f1c09fd2">TII</a> and <a href="#a3870dfac7df420149911b3e81c6c155a">TRI</a>.</p>

</div>
</div>

### end() {#a303e01bf517a6275123cfb03d0703f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLocIterator LiveDebugValues::MLocTracker::end ()</td>
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



<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>.</p>


<p>Referenced by <a href="#a217987fff459e088b64f179204e120f1">locations</a>.</p>

</div>
</div>

### getLocID() {#a2a28f143303b39650c069b1ce0925287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::getLocID (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>Produce location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for a <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>.</p>


<p>Provides some small amount of type safety.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Reg</td>
<td class="doxyParamItemDescription"><p>The register we're looking up.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#ad4b28d7abd903bca80aebdd56d893e8b">defReg</a>, <a href="#a1e7aca955e2c1f76d2f20f4475fe716d">getLocID</a>, <a href="#a88df5839a1471739fba42290c3a8279a">getRegMLoc</a>, <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>, <a href="#acb5a8547e6be549b193c89c9202889df">readReg</a>, <a href="#a5f3e7fca669ee92300565d5e78098311">setReg</a> and <a href="#a8c013a9da07953941f1e4e464d75db00">wipeRegister</a>.</p>

</div>
</div>

### getLocID() {#a1e7aca955e2c1f76d2f20f4475fe716d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::getLocID (<a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> Spill, unsigned SpillSubReg)</td>
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

<p>Produce location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for a spill position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Spill</td>
<td class="doxyParamItemDescription"><p>The number of the spill we're fetching the location for.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SpillSubReg</td>
<td class="doxyParamItemDescription"><p>Subregister within the spill we're addressing.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a3870dfac7df420149911b3e81c6c155a">TRI</a>.</p>

</div>
</div>

### getLocID() {#a223c8809c8643ad30bae41da7699b608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::getLocID (<a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> Spill, <a href="#a758eab2c8cea4d5486874624dba188b4">StackSlotPos</a> Idx)</td>
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

<p>Produce location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for a spill position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Spill</td>
<td class="doxyParamItemDescription"><p>The number of the spill we're fetching the location for. \apram SpillIdx size/offset within the spill slot to be addressed.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>, <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a> and <a href="#a5afcbfb84f0bb09c726e9a777d9f01e7">StackSlotIdxes</a>.</p>

</div>
</div>

### getLocSizeInBits() {#a00b889b10d5eaeb7be44d959e67263c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::getLocSizeInBits (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L)</td>
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

<p>How large is this location (aka, how wide is a value defined there?).</p>

<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a87fc8660fb193f626f9e9a6f0244108e">isSpill</a>, <a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#ae1a29742ce2fd47f4b4769dfe5a44f9e">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="#a3870dfac7df420149911b3e81c6c155a">TRI</a>.</p>


<p>Referenced by <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>.</p>

</div>
</div>

### getNumLocs() {#a48b9880cdbbdc53b8e5446db5dede09b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::getNumLocs ()</td>
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



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>.</p>

</div>
</div>

### getOrTrackSpillLoc() {#a0ec8c44bc2b0efa41c2a6583f9d75f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; SpillLocationNo &gt; MLocTracker::getOrTrackSpillLoc (<a href="/web-llvm/docs/api/structs/livedebugvalues/spillloc">SpillLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> for <a href="/web-llvm/docs/api/structs/livedebugvalues/spillloc">SpillLoc</a> <span class="doxyComputerOutput">L</span>, creating a new one if it's not tracked.</p>


<p>Returns std::nullopt when in scenarios where a spill slot could be tracked, but we would likely run into resource limitations.</p>


<p>Declaration at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a2017e35cd152cf2e3885ea8ed8e3d8f5">CurBB</a>, <a href="#a1c44cbd0dca6d3e9736ce4f240af2e25">getSpillIDWithIdx</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno/#a2e309fd3b79f17ba6213f7eb9d637329">LiveDebugValues::SpillLocationNo::id</a>, <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a>, <a href="#ab8795e147779aed8a5d0af6783babaa0">SpillLocs</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp/#ad6ba0b6b6e6515414554417edb06e073">StackWorkingSetLimit</a>.</p>

</div>
</div>

### getRegMLoc() {#a88df5839a1471739fba42290c3a8279a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIdx LiveDebugValues::MLocTracker::getRegMLoc (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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

<p>Determine the <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> of an existing register.</p>

<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a> and <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a>.</p>

</div>
</div>

### getSpillIDWithIdx() {#a1c44cbd0dca6d3e9736ce4f240af2e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::getSpillIDWithIdx (<a href="/web-llvm/docs/api/classes/livedebugvalues/spilllocationno">SpillLocationNo</a> Spill, unsigned Idx)</td>
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

<p>Given a spill number, and a slot within the spill, calculate the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number for that location.</p>

<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a> and <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a>.</p>


<p>Referenced by <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>.</p>

</div>
</div>

### getSpillMLoc() {#afd78a5b47f366715a6871891a6ad5fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIdx LiveDebugValues::MLocTracker::getSpillMLoc (unsigned SpillID)</td>
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



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a>.</p>

</div>
</div>

### IDAsString() {#a70d5f445ba9f76ce9d0a11bc11e8e1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string MLocTracker::IDAsString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &amp; Num)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1008 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a9313c0181a7f6ea6097163d55a4a7694">LiveDebugValues::ValueIDNum::asString</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#af0ee865517c9747fa74f9eb3ed54578a">LiveDebugValues::ValueIDNum::getLoc</a> and <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop/#a645a31ec228d2d3f5ec064b726514cd2">LiveDebugValues::DbgOp::dump</a>.</p>

</div>
</div>

### isRegisterTracked() {#a0975fbd8e22dcc611900504cbe982610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::MLocTracker::isRegisterTracked (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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

<p>Is register R currently tracked by <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a>?</p>

<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a>.</p>

</div>
</div>

### isSpill() {#a87fc8660fb193f626f9e9a6f0244108e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveDebugValues::MLocTracker::isSpill (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> Idx)</td>
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

<p>Return true if Idx is a spill machine location.</p>

<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a> and <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>.</p>


<p>Referenced by <a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a>.</p>

</div>
</div>

### loadFromArray() {#a0f6a2afd0fe02e3fcfcc5d75d186c21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::loadFromArray (<a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a7697a3c717033a44ba7f9b272c1d5331">ValueTable</a> &amp; Locs, unsigned NewCurBB)</td>
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

<p>Load values for each location from array of ValueIDNums.</p>


<p>Take current bbnum just in case we read a value from a hitherto untouched register.</p>


<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a2017e35cd152cf2e3885ea8ed8e3d8f5">CurBB</a> and <a href="#a217987fff459e088b64f179204e120f1">locations</a>.</p>

</div>
</div>

### locations() {#a217987fff459e088b64f179204e120f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; MLocIterator &gt; LiveDebugValues::MLocTracker::locations ()</td>
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

<p>Return a range over all locations currently tracked.</p>

<p>Definition at line 1002 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a3ac227f75996b7c2ab468a3faa25711c">begin</a>, <a href="#a303e01bf517a6275123cfb03d0703f08">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#ad60ba0b6dcb54a7fe37863ceb0165626">dump</a>, <a href="#af0c9cdac0acbe1745277e6e9544aa575">dump_mloc_map</a>, <a href="#a0f6a2afd0fe02e3fcfcc5d75d186c21b">loadFromArray</a>, <a href="#abc84cf80598821cf657ee831fce024bc">setMPhis</a> and <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### locIDToSpill() {#a63cf4d79a939e187701ac667cb07f5d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpillLocationNo LiveDebugValues::MLocTracker::locIDToSpill (unsigned ID)</td>
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

<p>Return the spill number that a location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> corresponds to.</p>

<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a> and <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a>.</p>


<p>Referenced by <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>.</p>

</div>
</div>

### locIDToSpillIdx() {#af39200a4599a5fc61a89ca83ce64598a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackSlotPos LiveDebugValues::MLocTracker::locIDToSpillIdx (unsigned ID)</td>
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

<p>Returns the spill-slot size/offs that a location <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> corresponds to.</p>

<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>, <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a> and <a href="#a6fa795efcfec488fc9683b69b1f9a4d3">StackIdxesToPos</a>.</p>


<p>Referenced by <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>, <a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a> and <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a>.</p>

</div>
</div>

### LocIdxToName() {#afe9d19d27dd82ae73f86937cb41c3d8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string MLocTracker::LocIdxToName (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a52ff73f5c87e0fb78fbdca0465300c95">llvm::concat</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a529bd775f25e1c6ea4a96b34a5d8bde6">llvm::Twine::concat</a>, <a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a>, <a href="#ab2d1c5bd4bf56e5b4124fa4088f5c5d9">NumSlotIdxes</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a> and <a href="#a3870dfac7df420149911b3e81c6c155a">TRI</a>.</p>


<p>Referenced by <a href="#ad60ba0b6dcb54a7fe37863ceb0165626">dump</a>, <a href="/web-llvm/docs/api/structs/livedebugvalues/resolveddbgop/#ae0c00dfb25229694b92d71199bfaca22">LiveDebugValues::ResolvedDbgOp::dump</a>, <a href="#af0c9cdac0acbe1745277e6e9544aa575">dump_mloc_map</a> and <a href="#a70d5f445ba9f76ce9d0a11bc11e8e1a9">IDAsString</a>.</p>

</div>
</div>

### lookupOrTrackRegister() {#a5c7000ce75181a4ad413b79566e11eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIdx LiveDebugValues::MLocTracker::lookupOrTrackRegister (unsigned ID)</td>
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



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a> and <a href="#ae0c12fcc919645ec5ae40a9763d756ba">trackRegister</a>.</p>


<p>Referenced by <a href="#ad4b28d7abd903bca80aebdd56d893e8b">defReg</a>, <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>, <a href="#acb5a8547e6be549b193c89c9202889df">readReg</a> and <a href="#a5f3e7fca669ee92300565d5e78098311">setReg</a>.</p>

</div>
</div>

### readMLoc() {#ab8ae8456399284b13679782065ee5dfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueIDNum LiveDebugValues::MLocTracker::readMLoc (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L)</td>
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

<p>Read the value of a particular location.</p>

<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>.</p>

</div>
</div>

### readReg() {#acb5a8547e6be549b193c89c9202889df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueIDNum LiveDebugValues::MLocTracker::readReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a> and <a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a>.</p>

</div>
</div>

### reset() {#a66a31574ce11e5d8dc78ed9a845305c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::reset ()</td>
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

<p>Wipe any un-necessary location records after traversing a block.</p>

<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Reference <a href="#ab115d98ec0127b8b019aae3e5e296efc">Masks</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### setMLoc() {#a8ed8c7355168afd27f9f47f505026c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::setMLoc (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> Num)</td>
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

<p>Set a locaiton to a certain value.</p>

<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>.</p>

</div>
</div>

### setMPhis() {#abc84cf80598821cf657ee831fce024bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::setMPhis (unsigned NewCurBB)</td>
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

<p>Reset all locations to contain a PHI value at the designated block.</p>


<p>Used sometimes for actual PHI values, othertimes to indicate the block entry value (before any more information is known).</p>


<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a2017e35cd152cf2e3885ea8ed8e3d8f5">CurBB</a> and <a href="#a217987fff459e088b64f179204e120f1">locations</a>.</p>

</div>
</div>

### setReg() {#a5f3e7fca669ee92300565d5e78098311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::setReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> ValueID)</td>
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

<p>Set a register to a value number.</p>


<p>To be used if the value number is known in advance.</p>


<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a> and <a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a>.</p>

</div>
</div>

### trackRegister() {#ae0c12fcc919645ec5ae40a9763d756ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocIdx MLocTracker::trackRegister (unsigned ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> for an untracked register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Initialize it to either an mphi value representing a live-in, or a recent register mask clobber.</p>


<p>Declaration at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2017e35cd152cf2e3885ea8ed8e3d8f5">CurBB</a>, <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#ab115d98ec0127b8b019aae3e5e296efc">Masks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a>.</p>

</div>
</div>

### wipeRegister() {#a8c013a9da07953941f1e4e464d75db00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::MLocTracker::wipeRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R)</td>
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

<p>Reset a register value to zero / empty.</p>


<p>Needed to replicate the VarLoc implementation where a copy to/from a register effectively clears the contents of the source register. (Values can only have one machine location in VarLocBasedImpl).</p>


<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a98d44bec6b754ac8786ab97f219f06f1">LiveDebugValues::ValueIDNum::EmptyValue</a>, <a href="#a2a28f143303b39650c069b1ce0925287">getLocID</a>, <a href="#a9b700e192036873e9756f231c9213a34">LocIDToLocIdx</a> and <a href="#a91fd5d450920e56cbde71ab8708fbab9">LocIdxToIDNum</a>.</p>

</div>
</div>

### writeRegMask() {#a73d25ebef02d1312bd901c694d7321ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MLocTracker::writeRegMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> * MO, unsigned CurBB, unsigned InstID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> a RegMask operand being executed.</p>


<p>Defs any register we currently track, stores a pointer to the mask in case we have to account for it later.</p>


<p>Declaration at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>, definition at line 1110 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ae4ecf5483b94e2bb72967b80cc2008d2">llvm::MachineOperand::clobbersPhysReg</a>, <a href="#a2017e35cd152cf2e3885ea8ed8e3d8f5">CurBB</a>, <a href="#ad4b28d7abd903bca80aebdd56d893e8b">defReg</a>, <a href="#a217987fff459e088b64f179204e120f1">locations</a>, <a href="#a12a921bb359eb2ab39e43e4c4ba780f3">LocIdxToLocID</a>, <a href="#ab115d98ec0127b8b019aae3e5e296efc">Masks</a>, <a href="#a3d106e52bda90530904b18edf24f2286">NumRegs</a> and <a href="#a2773f3976918a270bac316739f66ffd5">SPAliases</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CurBB {#a2017e35cd152cf2e3885ea8ed8e3d8f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::CurBB = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 730 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>, <a href="#a0f6a2afd0fe02e3fcfcc5d75d186c21b">loadFromArray</a>, <a href="#abc84cf80598821cf657ee831fce024bc">setMPhis</a>, <a href="#ae0c12fcc919645ec5ae40a9763d756ba">trackRegister</a> and <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### LocIDToLocIdx {#a9b700e192036873e9756f231c9213a34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;LocIdx&gt; LiveDebugValues::MLocTracker::LocIDToLocIdx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>"Map" of machine location IDs (i.e., raw register or spill number) to the <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> key / number for that location.</p>


<p>There are always at least as many as the number of registers on the target – if the value in the register is not being tracked, then the <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> value will be zero. New entries are appended if a new spill slot begins being tracked. This, and the corresponding reverse map persist for the analysis of the whole function, and is necessarying for decoding various vectors of values.</p>


<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>, <a href="#a88df5839a1471739fba42290c3a8279a">getRegMLoc</a>, <a href="#afd78a5b47f366715a6871891a6ad5fb0">getSpillMLoc</a>, <a href="#a0975fbd8e22dcc611900504cbe982610">isRegisterTracked</a>, <a href="#a5c7000ce75181a4ad413b79566e11eea">lookupOrTrackRegister</a>, <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a> and <a href="#a8c013a9da07953941f1e4e464d75db00">wipeRegister</a>.</p>

</div>
</div>

### LocIdxToIDNum {#a91fd5d450920e56cbde71ab8708fbab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocToValueType LiveDebugValues::MLocTracker::LocIdxToIDNum</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of LocIdxes to the ValueIDNums that they store.</p>


<p>This is tightly packed, entries only exist for locations that are being tracked.</p>


<p>Definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a3ac227f75996b7c2ab468a3faa25711c">begin</a>, <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#ad4b28d7abd903bca80aebdd56d893e8b">defReg</a>, <a href="#a303e01bf517a6275123cfb03d0703f08">end</a>, <a href="#a48b9880cdbbdc53b8e5446db5dede09b">getNumLocs</a>, <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>, <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>, <a href="#ab8ae8456399284b13679782065ee5dfc">readMLoc</a>, <a href="#acb5a8547e6be549b193c89c9202889df">readReg</a>, <a href="#a8ed8c7355168afd27f9f47f505026c54">setMLoc</a>, <a href="#a5f3e7fca669ee92300565d5e78098311">setReg</a>, <a href="#ae0c12fcc919645ec5ae40a9763d756ba">trackRegister</a> and <a href="#a8c013a9da07953941f1e4e464d75db00">wipeRegister</a>.</p>

</div>
</div>

### LocIdxToLocID {#a12a921bb359eb2ab39e43e4c4ba780f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;unsigned, LocIdxToIndexFunctor&gt; LiveDebugValues::MLocTracker::LocIdxToLocID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/inverse">Inverse</a> map of LocIDToLocIdx.</p>

<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>, <a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a>, <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>, <a href="#a87fc8660fb193f626f9e9a6f0244108e">isSpill</a>, <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a>, <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>, <a href="#ae0c12fcc919645ec5ae40a9763d756ba">trackRegister</a> and <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### Masks {#ab115d98ec0127b8b019aae3e5e296efc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;const MachineOperand *, unsigned&gt;, 32&gt; LiveDebugValues::MLocTracker::Masks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of register mask operands that have been observed.</p>


<p>Second part of pair indicates the instruction that they happened in. Used to reconstruct where defs happened if we start tracking a location later on.</p>


<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a66a31574ce11e5d8dc78ed9a845305c2">reset</a>, <a href="#ae0c12fcc919645ec5ae40a9763d756ba">trackRegister</a> and <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### MF {#ae1a29742ce2fd47f4b4769dfe5a44f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; LiveDebugValues::MLocTracker::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>, <a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### NumRegs {#a3d106e52bda90530904b18edf24f2286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::NumRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cached local copy of the number of registers the target has.</p>

<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>, <a href="#a223c8809c8643ad30bae41da7699b608">getLocID</a>, <a href="#a1c44cbd0dca6d3e9736ce4f240af2e25">getSpillIDWithIdx</a>, <a href="#a87fc8660fb193f626f9e9a6f0244108e">isSpill</a>, <a href="#a63cf4d79a939e187701ac667cb07f5d7">locIDToSpill</a>, <a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a>, <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a>, <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a> and <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### NumSlotIdxes {#ab2d1c5bd4bf56e5b4124fa4088f5c5d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LiveDebugValues::MLocTracker::NumSlotIdxes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of slot indexes the target has – distinct segments of a stack slot that can take on the value of a subregister, when a super-register is written to the stack.</p>

<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a223c8809c8643ad30bae41da7699b608">getLocID</a>, <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>, <a href="#a1c44cbd0dca6d3e9736ce4f240af2e25">getSpillIDWithIdx</a>, <a href="#a63cf4d79a939e187701ac667cb07f5d7">locIDToSpill</a>, <a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a>, <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### SPAliases {#a2773f3976918a270bac316739f66ffd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;Register, 8&gt; LiveDebugValues::MLocTracker::SPAliases</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When clobbering register masks, we chose to not believe the machine model and don't clobber SP.</p>


<p>Do the same for SP aliases, and for efficiency, keep a set of them here.</p>


<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a> and <a href="#a73d25ebef02d1312bd901c694d7321ee">writeRegMask</a>.</p>

</div>
</div>

### SpillLocs {#ab8795e147779aed8a5d0af6783babaa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UniqueVector&lt;SpillLoc&gt; LiveDebugValues::MLocTracker::SpillLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unique-ification of spill.</p>


<p>Used to number them – their LocID number is the index in SpillLocs minus one plus NumRegs.</p>


<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a> and <a href="#a0ec8c44bc2b0efa41c2a6583f9d75f21">getOrTrackSpillLoc</a>.</p>

</div>
</div>

### StackIdxesToPos {#a6fa795efcfec488fc9683b69b1f9a4d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, StackSlotPos&gt; LiveDebugValues::MLocTracker::StackIdxesToPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/inverse">Inverse</a> of StackSlotIdxes.</p>

<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#af39200a4599a5fc61a89ca83ce64598a">locIDToSpillIdx</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### StackSlotIdxes {#a5afcbfb84f0bb09c726e9a777d9f01e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;StackSlotPos, unsigned&gt; LiveDebugValues::MLocTracker::StackSlotIdxes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from a size/offset pair describing a position in a stack slot, to a numeric identifier for that position.</p>


<p>Allows easier identification of individual positions.</p>


<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#aaef75d1e01cf50cbf889096d2a6f3f89">clear</a>, <a href="#a223c8809c8643ad30bae41da7699b608">getLocID</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### TII {#a7bcfe28f8a994ea7a5fff050f1c09fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; LiveDebugValues::MLocTracker::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### TLI {#a2ceb7dab8f0063eec8dff6df6d2a3eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering&amp; LiveDebugValues::MLocTracker::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

### TRI {#a3870dfac7df420149911b3e81c6c155a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; LiveDebugValues::MLocTracker::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a88fd52c520cef6a03af97c37c308ae78">emitLoc</a>, <a href="#a1e7aca955e2c1f76d2f20f4475fe716d">getLocID</a>, <a href="#a00b889b10d5eaeb7be44d959e67263c6">getLocSizeInBits</a>, <a href="#afe9d19d27dd82ae73f86937cb41c3d8b">LocIdxToName</a> and <a href="#ae118b50388837cac4d807896b91f111e">MLocTracker</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
