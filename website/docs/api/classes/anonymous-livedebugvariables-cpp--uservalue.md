---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-livedebugvariables-cpp-/uservalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UserValue` Class Reference

<p>A user value is a part of a debug info user variable. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{LiveDebugVariables.cpp}::UserValue { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88fbb7df241556ac3a605cf5767b62ea">LDVImpl</a> = <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl">LiveDebugVariables::LDVImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348e6af0fa6606819a6c8ea7ec6b0583">UserValue</a> (const DILocalVariable *var, std::optional&lt; DIExpression::FragmentInfo &gt; Fragment, DebugLoc L, LocMap::Allocator &amp;alloc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a>. <a href="#a348e6af0fa6606819a6c8ea7ec6b0583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb602817973db88f42b1030aa3dae82">getLeader</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the leader of this value's equivalence class. <a href="#a2bb602817973db88f42b1030aa3dae82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14c0e3d9177db720bb2545802ec25c6">getNext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the next <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> in the equivalence class. <a href="#ad14c0e3d9177db720bb2545802ec25c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdf9051278b18a64c83cc047a3080de3">getLocationNo</a> (const MachineOperand &amp;LocMO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the location number that matches <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>. <a href="#acdf9051278b18a64c83cc047a3080de3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84a602692dd9ff042ba717d1b8f99e61">removeLocationIfUnused</a> (unsigned LocNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove (recycle) a location number. <a href="#a84a602692dd9ff042ba717d1b8f99e61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad49be349dc20188ea9201eddb54ad75">mapVirtRegs</a> (LDVImpl *LDV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure that all virtual register locations are mapped. <a href="#aad49be349dc20188ea9201eddb54ad75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f56e0c8e37796630334366257d1b7e3">addDef</a> (SlotIndex Idx, ArrayRef&lt; MachineOperand &gt; LocMOs, bool IsIndirect, bool IsList, const DIExpression &amp;Expr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a definition point to this user value. <a href="#a2f56e0c8e37796630334366257d1b7e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1066c542d3ccd99d3e740ad91aed49de">extendDef</a> (SlotIndex Idx, DbgVariableValue DbgValue, SmallDenseMap&lt; unsigned, std::pair&lt; LiveRange *, const VNInfo * &gt; &gt; &amp;LiveIntervalInfo, std::optional&lt; std::pair&lt; SlotIndex, SmallVector&lt; unsigned &gt; &gt; &gt; &amp;Kills, LiveIntervals &amp;LIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extend the current definition as far as possible down. <a href="#a1066c542d3ccd99d3e740ad91aed49de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0a0c1bb8dc69992e326ead7f5faf286">addDefsFromCopies</a> (DbgVariableValue DbgValue, SmallVectorImpl&lt; std::pair&lt; unsigned, LiveInterval * &gt; &gt; &amp;LocIntervals, SlotIndex KilledAt, SmallVectorImpl&lt; std::pair&lt; SlotIndex, DbgVariableValue &gt; &gt; &amp;NewDefs, MachineRegisterInfo &amp;MRI, LiveIntervals &amp;LIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The value in LI may be copies to other registers. <a href="#ac0a0c1bb8dc69992e326ead7f5faf286">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5addc8b01ca0cce0a572d5fe3ef86654">computeIntervals</a> (MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, LiveIntervals &amp;LIS, LexicalScopes &amp;LS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the live intervals of all locations after collecting all their def points. <a href="#a5addc8b01ca0cce0a572d5fe3ef86654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6349ba885032cac28990a282263667d7">splitRegister</a> (Register OldReg, ArrayRef&lt; Register &gt; NewRegs, LiveIntervals &amp;LIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace OldReg ranges with NewRegs ranges where NewRegs is live. <a href="#a6349ba885032cac28990a282263667d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3921084f5ef700564dcb83801124551">rewriteLocations</a> (VirtRegMap &amp;VRM, const MachineFunction &amp;MF, const TargetInstrInfo &amp;TII, const TargetRegisterInfo &amp;TRI, SpillOffsetMap &amp;SpillOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rewrite virtual register locations according to the provided virtual register map. <a href="#aa3921084f5ef700564dcb83801124551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c76eebc11caaa9225a4bfe146585a6">emitDebugValues</a> (VirtRegMap *VRM, LiveIntervals &amp;LIS, const TargetInstrInfo &amp;TII, const TargetRegisterInfo &amp;TRI, const SpillOffsetMap &amp;SpillOffsets, BlockSkipInstsMap &amp;BBSkipInstsMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recreate DBG_VALUE instruction from data structures. <a href="#a38c76eebc11caaa9225a4bfe146585a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a958d9ec8da6a69622eb3c408d14499ad">getDebugLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> of this <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a>. <a href="#a958d9ec8da6a69622eb3c408d14499ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cc6bb18e07abb863469007d3e3be069">print</a> (raw_ostream &amp;, const TargetRegisterInfo *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44baed52cf2f87ea1911a919be4774f">insertDebugValue</a> (MachineBasicBlock *MBB, SlotIndex StartIdx, SlotIndex StopIdx, DbgVariableValue DbgValue, ArrayRef&lt; bool &gt; LocSpills, ArrayRef&lt; unsigned &gt; SpillOffsets, LiveIntervals &amp;LIS, const TargetInstrInfo &amp;TII, const TargetRegisterInfo &amp;TRI, BlockSkipInstsMap &amp;BBSkipInstsMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a DBG_VALUE into MBB at Idx for <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a>. <a href="#ad44baed52cf2f87ea1911a919be4774f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523e8d14b86d4a45fde2a6aaf79b9ddb">splitLocation</a> (unsigned OldLocNo, ArrayRef&lt; Register &gt; NewRegs, LiveIntervals &amp;LIS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace OldLocNo ranges with NewRegs ranges where NewRegs is live. <a href="#a523e8d14b86d4a45fde2a6aaf79b9ddb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8a8b4539048eb2fffd3a67b02cdbc0">Variable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug info variable we are part of. <a href="#a9d8a8b4539048eb2fffd3a67b02cdbc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9de295d82dd5205bd3b073edf0a3c40">Fragment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The part of the variable we describe. <a href="#af9de295d82dd5205bd3b073edf0a3c40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284a2570c36cf9f60c205115365d96c1">dl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The debug location for the variable. <a href="#a284a2570c36cf9f60c205115365d96c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e11cbe70b13ab9b5eda9195933e28a">leader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalence class leader. <a href="#ac5e11cbe70b13ab9b5eda9195933e28a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2355759e35f4d68ca2a137d401b468c">next</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Next value in equivalence class, or null. <a href="#af2355759e35f4d68ca2a137d401b468c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e26f3340b8e6898c1a5de24e249249">locations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Numbered locations referenced by locmap. <a href="#a24e26f3340b8e6898c1a5de24e249249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#ab23073f2d9db5a8fc798c87b46f1795a">LocMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5326b54df6ec6b843283bfb578d8b95">locInts</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of slot indices where this value is live. <a href="#aa5326b54df6ec6b843283bfb578d8b95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff819ac63c9afd57fa6c5de46628eb7">trimmedDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of interval start indexes that have been trimmed to the lexical scope. <a href="#a2ff819ac63c9afd57fa6c5de46628eb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92af0086d7d75d96d35ccc03ebc66b4d">merge</a> (UserValue *L1, UserValue *L2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge equivalence classes. <a href="#a92af0086d7d75d96d35ccc03ebc66b4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A user value is a part of a debug info user variable.</p>


<p>A DBG_VALUE instruction notes that (a sub-register of) a virtual register holds part of a user variable. The part is identified by a byte offset.</p>


<p>UserValues are grouped into equivalence classes for easier searching. Two user values are related if they are held by the same virtual register. The equivalence class is the transitive closure of that relation.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LDVImpl {#a88fbb7df241556ac3a605cf5767b62ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{LiveDebugVariables.cpp}::UserValue::LDVImpl =  LiveDebugVariables::LDVImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### UserValue() {#a348e6af0fa6606819a6c8ea7ec6b0583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LiveDebugVariables.cpp}::UserValue::UserValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * var, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a2a09e6caba71ab15519f9e55ceb4d10d">DIExpression::FragmentInfo</a> &gt; Fragment, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> L, <a href="/web-llvm/docs/api/classes/llvm/intervalmap/#a6b645fcc5ae44b9a8e2fef275890ae4b">LocMap::Allocator</a> &amp; alloc)</td>
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

<p>Create a new <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a>.</p>

<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a2bb602817973db88f42b1030aa3dae82">getLeader</a>, <a href="#ad14c0e3d9177db720bb2545802ec25c6">getNext</a> and <a href="#a92af0086d7d75d96d35ccc03ebc66b4d">merge</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDef() {#a2f56e0c8e37796630334366257d1b7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LiveDebugVariables.cpp}::UserValue::addDef (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; LocMOs, bool IsIndirect, bool IsList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> &amp; Expr)</td>
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

<p>Add a definition point to this user value.</p>

<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="#acdf9051278b18a64c83cc047a3080de3">getLocationNo</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac3782d262b2a58da44d43c6d995aef9d">llvm::SlotIndex::getNextSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### addDefsFromCopies() {#ac0a0c1bb8dc69992e326ead7f5faf286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::addDefsFromCopies (<a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue">DbgVariableValue</a> DbgValue, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * &gt; &gt; &amp; LocIntervals, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> KilledAt, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue">DbgVariableValue</a> &gt; &gt; &amp; NewDefs, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The value in LI may be copies to other registers.</p>


<p>Determine if any of the copies are available at the kill points, and add defs if possible.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue"&gt;DbgValue&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>Location number of LI-&gt;reg, and <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LocIntervals</td>
<td class="doxyParamItemDescription"><p>Scan for copies of the value for each location in the corresponding LiveInterval-&gt;reg.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">KilledAt</td>
<td class="doxyParamItemDescription"><p>The point where the range of <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> could be extended.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] NewDefs</td>
<td class="doxyParamItemDescription"><p>Append (Idx, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a>) of inserted defs here.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#ac8891666086c72776f0c83fa8eef8b98">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::changeLocNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ae623a0f1ab59da851f2ebf1674d1fddb">llvm::VNInfo::def</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a1882fe2a570964e4c6abb0eac322beab">llvm::LiveIntervals::getInstructionFromIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="#acdf9051278b18a64c83cc047a3080de3">getLocationNo</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ac3782d262b2a58da44d43c6d995aef9d">llvm::SlotIndex::getNextSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a11cd70de340f310acc70781d57a00136">llvm::LiveIntervals::hasInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1912d4fbc40c61a12b1f770ad54dfd74">llvm::MachineInstr::isCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>


<p>Referenced by <a href="#a5addc8b01ca0cce0a572d5fe3ef86654">computeIntervals</a>.</p>

</div>
</div>

### computeIntervals() {#a5addc8b01ca0cce0a572d5fe3ef86654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::computeIntervals (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/classes/llvm/lexicalscopes">LexicalScopes</a> &amp; LS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the live intervals of all locations after collecting all their def points.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="#ac0a0c1bb8dc69992e326ead7f5faf286">addDefsFromCopies</a>, <a href="#a1066c542d3ccd99d3e740ad91aed49de">extendDef</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#ae300b9628007f942d7a1b2cfaedc7d48">llvm::SlotIndexes::getIndexBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6f3043b29023d270fc4bc5062dff7cee">llvm::LiveIntervals::getInstructionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a8208eacaf02c9742c8ed7f09ec0837f3">llvm::LiveIntervals::getInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a10ffbec8bd7a2d9bc3c995e572ddc430">llvm::SlotIndex::getNextIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a334e584aeef0fcf744450fdf41fe8a84">llvm::LiveIntervals::getSlotIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a11cd70de340f310acc70781d57a00136">llvm::LiveIntervals::hasInterval</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### emitDebugValues() {#a38c76eebc11caaa9225a4bfe146585a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::emitDebugValues (<a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * VRM, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#adf31c9fb4f0ad550eeeb977362135cdf">SpillOffsetMap</a> &amp; SpillOffsets, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#ab17bc8e142c2f18a7576ea8276b0d124">BlockSkipInstsMap</a> &amp; BBSkipInstsMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recreate DBG_VALUE instruction from data structures.</p>

<p>Definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a7619711af4bb95253dea3e0783400f26">llvm::VirtRegMap::getMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a76163707e71807054d87648aa5e00dd7">llvm::LiveIntervals::getMBBEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#af3fe68c1ef3d401833b3d37cc222ead2">llvm::LiveIntervals::getMBBFromIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### extendDef() {#a1066c542d3ccd99d3e740ad91aed49de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::extendDef (<a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue">DbgVariableValue</a> DbgValue, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt; &gt; &amp; LiveIntervalInfo, std::optional&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned &gt; &gt; &gt; &amp; Kills, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extend the current definition as far as possible down.</p>


<p>Stop when meeting an existing def or when leaving the live range of VNI. End points where VNI is no longer live are added to Kills.</p>


<p>We only propagate DBG_VALUES locally here. <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a> performs a data-flow analysis to propagate them beyond basic block boundaries.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>Starting point for the definition.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">&lt;a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue"&gt;DbgValue&lt;/a&gt;</td>
<td class="doxyParamItemDescription"><p>value to propagate.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LiveIntervalInfo</td>
<td class="doxyParamItemDescription"><p>For each location number key in this map, restricts liveness to where the <a href="/web-llvm/docs/api/classes/llvm/liverange">LiveRange</a> has the value equal to the\ <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] Kills</td>
<td class="doxyParamItemDescription"><p>Append end points of VNI's live range to Kills.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LIS</td>
<td class="doxyParamItemDescription"><p>Live intervals analysis.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#afe8e59ffc86cb1736116e4dc8b86e26f">llvm::LiveRange::Segment::end</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a76163707e71807054d87648aa5e00dd7">llvm::LiveIntervals::getMBBEndIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#af3fe68c1ef3d401833b3d37cc222ead2">llvm::LiveIntervals::getMBBFromIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a1cde3a312b39ac23baecfce5fee662f7">llvm::LiveRange::getSegmentContaining</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#ac3d1b43d371bc68742232ec51d4a6321">llvm::LiveRange::Segment::valno</a>.</p>


<p>Referenced by <a href="#a5addc8b01ca0cce0a572d5fe3ef86654">computeIntervals</a>.</p>

</div>
</div>

### getDebugLoc() {#a958d9ec8da6a69622eb3c408d14499ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; anonymous{LiveDebugVariables.cpp}::UserValue::getDebugLoc ()</td>
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

<p>Return <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> of this <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a>.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### getLeader() {#a2bb602817973db88f42b1030aa3dae82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue * anonymous{LiveDebugVariables.cpp}::UserValue::getLeader ()</td>
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

<p>Get the leader of this value's equivalence class.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="#a348e6af0fa6606819a6c8ea7ec6b0583">UserValue</a>.</p>


<p>Referenced by <a href="#a92af0086d7d75d96d35ccc03ebc66b4d">merge</a>.</p>

</div>
</div>

### getLocationNo() {#acdf9051278b18a64c83cc047a3080de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{LiveDebugVariables.cpp}::UserValue::getLocationNo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; LocMO)</td>
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

<p>Return the location number that matches <a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a>.</p>


<p>For undef values we always return location number UndefLocNo without inserting anything in locations. Since locations is a vector and the location number is the position in the vector and UndefLocNo is ~0, we would need a very big vector to put the value at the right position.</p>


<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad7f2dc64214551418f486026ffc95fa4">llvm::MachineOperand::isIdenticalTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a016dd6336a9fdf02777eef5db4ee0478add4810f34bbc590fbe2638613bf7ebf5">UndefLocNo</a>.</p>


<p>Referenced by <a href="#a2f56e0c8e37796630334366257d1b7e3">addDef</a> and <a href="#ac0a0c1bb8dc69992e326ead7f5faf286">addDefsFromCopies</a>.</p>

</div>
</div>

### getNext() {#ad14c0e3d9177db720bb2545802ec25c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue * anonymous{LiveDebugVariables.cpp}::UserValue::getNext ()</td>
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

<p>Return the next <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> in the equivalence class.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="#a348e6af0fa6606819a6c8ea7ec6b0583">UserValue</a>.</p>

</div>
</div>

### mapVirtRegs() {#aad49be349dc20188ea9201eddb54ad75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::mapVirtRegs (<a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl">LDVImpl</a> * LDV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ensure that all virtual register locations are mapped.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#a5c8e1e68d0b79b7c31776fa78023d667">llvm::LiveDebugVariables::LDVImpl::mapVirtReg</a>.</p>

</div>
</div>

### print() {#a7cc6bb18e07abb863469007d3e3be069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> * TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a6bcdb97daefc7a1ed36de42e22be84b2">printExtendedName</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### removeLocationIfUnused() {#a84a602692dd9ff042ba717d1b8f99e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LiveDebugVariables.cpp}::UserValue::removeLocationIfUnused (unsigned LocNo)</td>
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

<p>Remove (recycle) a location number.</p>


<p>If <span class="doxyComputerOutput">LocNo</span> still is used by the locInts nothing is done.</p>


<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### rewriteLocations() {#aa3921084f5ef700564dcb83801124551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::rewriteLocations (<a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; VRM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#adf31c9fb4f0ad550eeeb977362135cdf">SpillOffsetMap</a> &amp; SpillOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rewrite virtual register locations according to the provided virtual register map.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the stack slot offsets for the locations that were spilled.</p>


<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mapvector/#aa610cab7ee61e36a6d1d122fc252c278">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adf4e7878fc0b3b8dcde545178564190d">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#afda3f1971b3e44709267be818ffd3035">llvm::MachineOperand::CreateFI</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a785a4e2daf4e5bf3f0836adbc4fb7e65">llvm::VirtRegMap::getPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a32846fd2d98022e7b336962f85411a42">llvm::VirtRegMap::getStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ab28bf4ffd3e2223dab0527c9d7e18288">llvm::VirtRegMap::hasPhys</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ad0df6033e4012261f7531e62274cf99c">llvm::VirtRegMap::isAssignedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ad2e99ae080aa934d64b0ff504dab0158">llvm::VirtRegMap::NO_STACK_SLOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### splitRegister() {#a6349ba885032cac28990a282263667d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UserValue::splitRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; NewRegs, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace OldReg ranges with NewRegs ranges where NewRegs is live.</p>


<p>Returns true if any changes were made.</p>


<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### insertDebugValue() {#ad44baed52cf2f87ea1911a919be4774f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UserValue::insertDebugValue (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> StartIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> StopIdx, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue">DbgVariableValue</a> DbgValue, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; bool &gt; LocSpills, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; SpillOffsets, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#ab17bc8e142c2f18a7576ea8276b0d124">BlockSkipInstsMap</a> &amp; BBSkipInstsMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a DBG_VALUE into MBB at Idx for <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a>.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### splitLocation() {#a523e8d14b86d4a45fde2a6aaf79b9ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UserValue::splitLocation (unsigned OldLocNo, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; NewRegs, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; LIS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace OldLocNo ranges with NewRegs ranges where NewRegs is live.</p>


<p>Returns true if any changes were made.</p>


<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### dl {#a284a2570c36cf9f60c205115365d96c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc anonymous{LiveDebugVariables.cpp}::UserValue::dl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug location for the variable.</p>


<p>This is used by dwarf writer to find lexical scope.</p>


<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### Fragment {#af9de295d82dd5205bd3b073edf0a3c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt;DIExpression::FragmentInfo&gt; anonymous{LiveDebugVariables.cpp}::UserValue::Fragment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The part of the variable we describe.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### leader {#ac5e11cbe70b13ab9b5eda9195933e28a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue* anonymous{LiveDebugVariables.cpp}::UserValue::leader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Equivalence class leader.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### locations {#a24e26f3340b8e6898c1a5de24e249249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineOperand, 4&gt; anonymous{LiveDebugVariables.cpp}::UserValue::locations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Numbered locations referenced by locmap.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### locInts {#aa5326b54df6ec6b843283bfb578d8b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocMap anonymous{LiveDebugVariables.cpp}::UserValue::locInts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of slot indices where this value is live.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### next {#af2355759e35f4d68ca2a137d401b468c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue* anonymous{LiveDebugVariables.cpp}::UserValue::next = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Next value in equivalence class, or null.</p>

<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### trimmedDefs {#a2ff819ac63c9afd57fa6c5de46628eb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallSet&lt;SlotIndex, 2&gt; anonymous{LiveDebugVariables.cpp}::UserValue::trimmedDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of interval start indexes that have been trimmed to the lexical scope.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

### Variable {#a9d8a8b4539048eb2fffd3a67b02cdbc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DILocalVariable* anonymous{LiveDebugVariables.cpp}::UserValue::Variable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The debug info variable we are part of.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### merge() {#a92af0086d7d75d96d35ccc03ebc66b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UserValue * anonymous{LiveDebugVariables.cpp}::UserValue::merge (<a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> * L1, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue">UserValue</a> * L2)</td>
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

<p>Merge equivalence classes.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a>.</p>


<p>References <a href="#a2bb602817973db88f42b1030aa3dae82">getLeader</a> and <a href="#a348e6af0fa6606819a6c8ea7ec6b0583">UserValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#a5c8e1e68d0b79b7c31776fa78023d667">llvm::LiveDebugVariables::LDVImpl::mapVirtReg</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp">LiveDebugVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
