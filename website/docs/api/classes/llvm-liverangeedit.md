---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/liverangeedit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveRangeEdit` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LiveRangeEdit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">llvm/CodeGen/LiveRangeEdit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/delegate">Delegate</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a61884e0ee025f349013096bbaf969">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;::const_iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iterator for accessing the new registers added by this edit. <a href="#a92a61884e0ee025f349013096bbaf969">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e9af8c7956755e07a294e42c5bef0c">ToShrinkSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *, 8 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a704fd862d35d9131d49d21eb04bea6a2">LiveRangeEdit</a> (const LiveInterval *parent, SmallVectorImpl&lt; Register &gt; &amp;newRegs, MachineFunction &amp;MF, LiveIntervals &amp;lis, VirtRegMap *vrm, Delegate *delegate=nullptr, SmallPtrSet&lt; MachineInstr *, 32 &gt; *deadRemats=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> for breaking down parent into smaller pieces. <a href="#a704fd862d35d9131d49d21eb04bea6a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a14d737ebff3ca62e3832159042715a">~LiveRangeEdit</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a989ed5e9a7610a873a79ea663f83b814">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2d157d94da9ea6da55d19a1fa8d9247">getReg</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92a61884e0ee025f349013096bbaf969">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26bf8b8e73249be10568c470c320d0f">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a92a61884e0ee025f349013096bbaf969">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a080c77cf5c8c9d4bc738289d9d34b">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e56ee2f27a7c83b385e3c879fe4ee90">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1de6c78789e3f41a5721e581ec3e981b">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3456a41d2c4561bb42f944f3d22a9d2b">get</a> (unsigned idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae900d06706a552fb8fa8c34a47d294f7">pop_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pop_back - It allows <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> users to drop new registers. <a href="#ae900d06706a552fb8fa8c34a47d294f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2c5b3a9e319c21b55d9de1c3791eea2">regs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e01dee66b5c7b7118a17b987a8446bd">createFrom</a> (Register OldReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createFrom - Create a new virtual register based on OldReg. <a href="#a5e01dee66b5c7b7118a17b987a8446bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f3c35c09c2783a6ddba17ccecd8c59">createEmptyInterval</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>create - Create a new register with the same class and original slot as parent. <a href="#a69f3c35c09c2783a6ddba17ccecd8c59">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09642c7465db9ebf2e384ba9ada8b3a3">create</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff06b5e0f98141b098d89db4e93f472b">anyRematerializable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>anyRematerializable - Return true if any parent values may be rematerializable. <a href="#aff06b5e0f98141b098d89db4e93f472b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaf1429d245f871e41187accdce34e06">checkRematerializable</a> (VNInfo *VNI, const MachineInstr *DefMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkRematerializable - Manually add VNI to the list of rematerializable values if DefMI may be rematerializable. <a href="#aeaf1429d245f871e41187accdce34e06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad930b47a8263b4fcc37e6209e387b897">allUsesAvailableAt</a> (const MachineInstr *OrigMI, SlotIndex OrigIdx, SlotIndex UseIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>allUsesAvailableAt - Return true if all registers used by OrigMI at OrigIdx are also available with the same value at UseIdx. <a href="#ad930b47a8263b4fcc37e6209e387b897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8377265a59783069f11e01edc8e3edc">canRematerializeAt</a> (Remat &amp;RM, VNInfo *OrigVNI, SlotIndex UseIdx, bool cheapAsAMove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>canRematerializeAt - Determine if ParentVNI can be rematerialized at UseIdx. <a href="#af8377265a59783069f11e01edc8e3edc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2480b715c870bd7fc306f70c3fa1dc8">rematerializeAt</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, Register DestReg, const Remat &amp;RM, const TargetRegisterInfo &amp;, bool Late=false, unsigned SubIdx=0, MachineInstr *ReplaceIndexMI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>rematerializeAt - Rematerialize RM.ParentVNI into DestReg by inserting an instruction into MBB before MI. <a href="#ad2480b715c870bd7fc306f70c3fa1dc8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af296216a2d7d12b2cc2273effb7da1bd">markRematerialized</a> (const VNInfo *ParentVNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markRematerialized - explicitly mark a value as rematerialized after doing it manually. <a href="#af296216a2d7d12b2cc2273effb7da1bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa359a34c1dd19a35f80029e446e8052">didRematerialize</a> (const VNInfo *ParentVNI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>didRematerialize - Return true if ParentVNI was rematerialized anywhere. <a href="#afa359a34c1dd19a35f80029e446e8052">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e11e331657883b7bdeb2b8ef9bf856">eraseVirtReg</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eraseVirtReg - Notify the delegate that Reg is no longer in use, and try to erase it from LIS. <a href="#a18e11e331657883b7bdeb2b8ef9bf856">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add47e6d974ce584ea3fa3fc80ee34259">eliminateDeadDefs</a> (SmallVectorImpl&lt; MachineInstr * &gt; &amp;Dead, ArrayRef&lt; Register &gt; RegsBeingSpilled={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eliminateDeadDefs - Try to delete machine instructions that are now dead (allDefsAreDead returns true). <a href="#add47e6d974ce584ea3fa3fc80ee34259">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c15e4226ea85c6c5ffdb7b907023b85">calculateRegClassAndHint</a> (MachineFunction &amp;, VirtRegAuxInfo &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>calculateRegClassAndHint - Recompute register class and hint for each new register. <a href="#a6c15e4226ea85c6c5ffdb7b907023b85">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4b9c19f1d7bde9cf15a3295143c398">scanRemattable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>scanRemattable - Identify the Parent values that may rematerialize. <a href="#aec4b9c19f1d7bde9cf15a3295143c398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9077e6ce66024661a1f78392ad87c74a">foldAsLoad</a> (LiveInterval *LI, SmallVectorImpl&lt; MachineInstr * &gt; &amp;Dead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>foldAsLoad - If LI has a single use and a single def that can be folded as a load, eliminate the register by folding the def into the use. <a href="#a9077e6ce66024661a1f78392ad87c74a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb81c04e56f60d191776e4a383567e1">eliminateDeadDef</a> (MachineInstr *MI, ToShrinkSet &amp;ToShrink)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for eliminateDeadDefs. <a href="#abfb81c04e56f60d191776e4a383567e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852eb077aeede08b56e1a47c83cecc0a">MRI_NoteNewVirtualRegister</a> (Register VReg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> callback to notify when new virtual registers are created. <a href="#a852eb077aeede08b56e1a47c83cecc0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebee39d75c7a68e8a58c438578a140de">useIsKill</a> (const LiveInterval &amp;LI, const MachineOperand &amp;MO) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> <span class="doxyComputerOutput">MO</span> is a last use/kill either in the main live range of <span class="doxyComputerOutput">LI</span> or in one of the matching subregister ranges. <a href="#aebee39d75c7a68e8a58c438578a140de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f4d0d7950e758d0f9bc8e912cc663d1">createEmptyIntervalFrom</a> (Register OldReg, bool createSubRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new empty interval based on OldReg. <a href="#a3f4d0d7950e758d0f9bc8e912cc663d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92512c0dc13b9fa34ddff2b4670d2fc9">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5c13ae4c59abf845767f4dd5cd2d88">NewRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade6ab0b6da879410f4eb4d422a780af7">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17489db6a65127f17251aef566bbbe5">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746358dbbff06052d96c3c2266d59f36">VRM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd98603f84f326966c0270946fc00981">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate">Delegate</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd1867695497f54607155afde4eb1c7">TheDelegate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43c00b38040a6e8bed43d12c8dbfcc62">FirstNew</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FirstNew - Index of the first register added to NewRegs. <a href="#a43c00b38040a6e8bed43d12c8dbfcc62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa10b31e5a7652be9c07f9ab1a3bd2989">ScannedRemattable</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ScannedRemattable - true when remattable values have been identified. <a href="#aa10b31e5a7652be9c07f9ab1a3bd2989">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt; *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184568c315ba9cfc5b067ebd619de6dd">DeadRemats</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DeadRemats - The saved instructions which have already been dead after rematerialization but not deleted yet – to be done in postOptimization. <a href="#a184568c315ba9cfc5b067ebd619de6dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad541aaf7fccb2c06d8b147fcd057e9d">Remattable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remattable - Values defined by remattable instructions as identified by tii.isTriviallyReMaterializable(). <a href="#aad541aaf7fccb2c06d8b147fcd057e9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d37aa2092d3093964d3aa17ed50d497">Rematted</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Rematted - Values that were actually rematted, and so need to have their live range trimmed or entirely removed. <a href="#a3d37aa2092d3093964d3aa17ed50d497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a92a61884e0ee025f349013096bbaf969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRangeEdit::iterator =  SmallVectorImpl&lt;Register&gt;::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Iterator for accessing the new registers added by this edit.</p>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ToShrinkSet {#ae0e9af8c7956755e07a294e42c5bef0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::LiveRangeEdit::ToShrinkSet =  SmallSetVector&lt;LiveInterval *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveRangeEdit() {#a704fd862d35d9131d49d21eb04bea6a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRangeEdit::LiveRangeEdit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * parent, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; newRegs, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp; lis, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> * vrm, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate">Delegate</a> * delegate=nullptr, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 32 &gt; * deadRemats=nullptr)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> for breaking down parent into smaller pieces.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">parent</td>
<td class="doxyParamItemDescription"><p>The register being spilled or split.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">newRegs</td>
<td class="doxyParamItemDescription"><p>List to receive any new registers created. This needn't be empty initially, any existing registers are ignored.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MF</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> the live range edit is taking place in.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">lis</td>
<td class="doxyParamItemDescription"><p>The collection of all live intervals in this function.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">vrm</td>
<td class="doxyParamItemDescription"><p>Map of virtual registers to physical registers for this function. If NULL, no virtual register map updates will be done. This could be the case if called before Regalloc.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">deadRemats</td>
<td class="doxyParamItemDescription"><p>The collection of all the instructions defining an original reg and are dead after remat.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Reference <a href="#a2e56ee2f27a7c83b385e3c879fe4ee90">size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LiveRangeEdit() {#a2a14d737ebff3ca62e3832159042715a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveRangeEdit::~LiveRangeEdit ()</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allUsesAvailableAt() {#ad930b47a8263b4fcc37e6209e387b897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeEdit::allUsesAvailableAt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * OrigMI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> OrigIdx, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> UseIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>allUsesAvailableAt - Return true if all registers used by OrigMI at OrigIdx are also available with the same value at UseIdx.</p>

<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#afe7daa73e4cee4edb9f137a8008dfb73">llvm::LiveRange::getVNInfoAt</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1c198291d6ee66150b76633cda8a1749">llvm::LiveInterval::hasSubRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#a0b73244049319d841fd11a238f35b5d1">llvm::SlotIndex::isSameInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/lanebitmask/#a60907035da962ba7bea74ffb9af977bd">llvm::LaneBitmask::none</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a9545a896d571165e9f43cf4b29a6d072">llvm::LiveInterval::subranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#af8377265a59783069f11e01edc8e3edc">canRematerializeAt</a>.</p>

</div>
</div>

### anyRematerializable() {#aff06b5e0f98141b098d89db4e93f472b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeEdit::anyRematerializable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>anyRematerializable - Return true if any parent values may be rematerializable.</p>


<p>This function must be called before any rematerialization is attempted.</p>


<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### begin() {#ab26bf8b8e73249be10568c470c320d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LiveRangeEdit::begin ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### calculateRegClassAndHint() {#a6c15e4226ea85c6c5ffdb7b907023b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeEdit::calculateRegClassAndHint (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo">VirtRegAuxInfo</a> &amp; VRAI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>calculateRegClassAndHint - Recompute register class and hint for each new register.</p>

<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#ab388ef162b7c6b9061678583f9fd0f16">llvm::VirtRegAuxInfo::calculateSpillWeightAndHint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a3456a41d2c4561bb42f944f3d22a9d2b">get</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a43c530c830206ecf5ad3359364634c75">llvm::TargetSubtargetInfo::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a2e56ee2f27a7c83b385e3c879fe4ee90">size</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### canRematerializeAt() {#af8377265a59783069f11e01edc8e3edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeEdit::canRematerializeAt (<a href="/web-llvm/docs/api/structs/llvm/liverangeedit/remat">Remat</a> &amp; RM, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * OrigVNI, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> UseIdx, bool cheapAsAMove)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>canRematerializeAt - Determine if ParentVNI can be rematerialized at UseIdx.</p>


<p>It is assumed that parent_.getVNINfoAt(UseIdx) == ParentVNI. When cheapAsAMove is set, only cheap remats are allowed.</p>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>References <a href="#ad930b47a8263b4fcc37e6209e387b897">allUsesAvailableAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### checkRematerializable() {#aeaf1429d245f871e41187accdce34e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeEdit::checkRematerializable (<a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * DefMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>checkRematerializable - Manually add VNI to the list of rematerializable values if DefMI may be rematerializable.</p>

<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>.</p>

</div>
</div>

### create() {#a09642c7465db9ebf2e384ba9ada8b3a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LiveRangeEdit::create ()</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>References <a href="#a5e01dee66b5c7b7118a17b987a8446bd">createFrom</a> and <a href="#ac2d157d94da9ea6da55d19a1fa8d9247">getReg</a>.</p>

</div>
</div>

### createEmptyInterval() {#a69f3c35c09c2783a6ddba17ccecd8c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval &amp; llvm::LiveRangeEdit::createEmptyInterval ()</td>
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

<p>create - Create a new register with the same class and original slot as parent.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Reference <a href="#ac2d157d94da9ea6da55d19a1fa8d9247">getReg</a>.</p>

</div>
</div>

### createFrom() {#a5e01dee66b5c7b7118a17b987a8446bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register LiveRangeEdit::createFrom (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createFrom - Create a new virtual register based on OldReg.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>Referenced by <a href="#a09642c7465db9ebf2e384ba9ada8b3a3">create</a>.</p>

</div>
</div>

### didRematerialize() {#afa359a34c1dd19a35f80029e446e8052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRangeEdit::didRematerialize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ParentVNI)</td>
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

<p>didRematerialize - Return true if ParentVNI was rematerialized anywhere.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### eliminateDeadDefs() {#add47e6d974ce584ea3fa3fc80ee34259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeEdit::eliminateDeadDefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; Dead, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; RegsBeingSpilled={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eliminateDeadDefs - Try to delete machine instructions that are now dead (allDefsAreDead returns true).</p>


<p>This may cause live intervals to be trimmed and further dead efs to be eliminated. RegsBeingSpilled lists registers currently being spilled by the register allocator. These registers should not be split into new intervals as currently those new intervals are not guaranteed to spill.</p>


<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a> and <a href="/web-llvm/docs/api/classes/llvm/liverange/#a687cab1756967efc8f0ce66105531755">llvm::LiveRange::RenumberValues</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#a597bb5d7ef9a22f44dbe867d8eaa7fd6">anonymous{InlineSpiller.cpp}::HoistSpillHelper::hoistAllSpills</a>.</p>

</div>
</div>

### empty() {#a1de6c78789e3f41a5721e581ec3e981b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRangeEdit::empty ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Reference <a href="#a2e56ee2f27a7c83b385e3c879fe4ee90">size</a>.</p>

</div>
</div>

### end() {#ab0a080c77cf5c8c9d4bc738289d9d34b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::LiveRangeEdit::end ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### eraseVirtReg() {#a18e11e331657883b7bdeb2b8ef9bf856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeEdit::eraseVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eraseVirtReg - Notify the delegate that Reg is no longer in use, and try to erase it from LIS.</p>

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### get() {#a3456a41d2c4561bb42f944f3d22a9d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LiveRangeEdit::get (unsigned idx)</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Referenced by <a href="#a6c15e4226ea85c6c5ffdb7b907023b85">calculateRegClassAndHint</a>.</p>

</div>
</div>

### getParent() {#a989ed5e9a7610a873a79ea663f83b814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval &amp; llvm::LiveRangeEdit::getParent ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ac2d157d94da9ea6da55d19a1fa8d9247">getReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/inlinespiller/#af74cc1b6ed58474b37bafc059339a964">anonymous{InlineSpiller.cpp}::InlineSpiller::spill</a>.</p>

</div>
</div>

### getReg() {#ac2d157d94da9ea6da55d19a1fa8d9247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::LiveRangeEdit::getReg ()</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>References <a href="#a989ed5e9a7610a873a79ea663f83b814">getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a>.</p>


<p>Referenced by <a href="#a09642c7465db9ebf2e384ba9ada8b3a3">create</a>, <a href="#a69f3c35c09c2783a6ddba17ccecd8c59">createEmptyInterval</a> and <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/inlinespiller/#af74cc1b6ed58474b37bafc059339a964">anonymous{InlineSpiller.cpp}::InlineSpiller::spill</a>.</p>

</div>
</div>

### markRematerialized() {#af296216a2d7d12b2cc2273effb7da1bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRangeEdit::markRematerialized (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * ParentVNI)</td>
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

<p>markRematerialized - explicitly mark a value as rematerialized after doing it manually.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### pop\_back() {#ae900d06706a552fb8fa8c34a47d294f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveRangeEdit::pop_back ()</td>
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

<p>pop_back - It allows <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> users to drop new registers.</p>


<p>The context is when an original def instruction of a register is dead after rematerialization, we still want to keep it for following rematerializations. We save the def instruction in DeadRemats, and replace the original dst register with a new dummy register so the live range of original dst register can be shrinked normally. We don't want to allocate phys register for the dummy register, so we want to drop it from the NewRegs set.</p>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### regs() {#aa2c5b3a9e319c21b55d9de1c3791eea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Register &gt; llvm::LiveRangeEdit::regs ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>.</p>

</div>
</div>

### rematerializeAt() {#ad2480b715c870bd7fc306f70c3fa1dc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotIndex LiveRangeEdit::rematerializeAt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DestReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/liverangeedit/remat">Remat</a> &amp; RM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; tri, bool Late=false, unsigned SubIdx=0, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * ReplaceIndexMI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>rematerializeAt - Rematerialize RM.ParentVNI into DestReg by inserting an instruction into MBB before MI.</p>


<p>The new instruction is mapped, but liveness is not updated. If ReplaceIndexMI is not null it will be replaced by new MI in the index map. Return the <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> of the new instruction.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### size() {#a2e56ee2f27a7c83b385e3c879fe4ee90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::LiveRangeEdit::size ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>


<p>Referenced by <a href="#a6c15e4226ea85c6c5ffdb7b907023b85">calculateRegClassAndHint</a>, <a href="#a1de6c78789e3f41a5721e581ec3e981b">empty</a> and <a href="#a704fd862d35d9131d49d21eb04bea6a2">LiveRangeEdit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createEmptyIntervalFrom() {#a3f4d0d7950e758d0f9bc8e912cc663d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval &amp; LiveRangeEdit::createEmptyIntervalFrom (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OldReg, bool createSubRanges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new empty interval based on OldReg.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### eliminateDeadDef() {#abfb81c04e56f60d191776e4a383567e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeEdit::eliminateDeadDef (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">ToShrinkSet</a> &amp; ToShrink)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for eliminateDeadDefs.</p>


<p>Find all live intervals that need to shrink, then remove the instruction.</p>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### foldAsLoad() {#a9077e6ce66024661a1f78392ad87c74a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeEdit::foldAsLoad (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; Dead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>foldAsLoad - If LI has a single use and a single def that can be folded as a load, eliminate the register by folding the def into the use.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### MRI\_NoteNewVirtualRegister() {#a852eb077aeede08b56e1a47c83cecc0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeEdit::MRI_NoteNewVirtualRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> callback to notify when new virtual registers are created.</p>

<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### scanRemattable() {#aec4b9c19f1d7bde9cf15a3295143c398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveRangeEdit::scanRemattable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>scanRemattable - Identify the Parent values that may rematerialize.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

### useIsKill() {#aebee39d75c7a68e8a58c438578a140de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveRangeEdit::useIsKill (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; LI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> <span class="doxyComputerOutput">MO</span> is a last use/kill either in the main live range of <span class="doxyComputerOutput">LI</span> or in one of the matching subregister ranges.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>, definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DeadRemats {#a184568c315ba9cfc5b067ebd619de6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr *, 32&gt;* llvm::LiveRangeEdit::DeadRemats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DeadRemats - The saved instructions which have already been dead after rematerialization but not deleted yet – to be done in postOptimization.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### FirstNew {#a43c00b38040a6e8bed43d12c8dbfcc62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::LiveRangeEdit::FirstNew</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FirstNew - Index of the first register added to NewRegs.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### LIS {#ac17489db6a65127f17251aef566bbbe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; llvm::LiveRangeEdit::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### MRI {#ade6ab0b6da879410f4eb4d422a780af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::LiveRangeEdit::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### NewRegs {#aba5c13ae4c59abf845767f4dd5cd2d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt;Register&gt;&amp; llvm::LiveRangeEdit::NewRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### Parent {#a92512c0dc13b9fa34ddff2b4670d2fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveInterval* const llvm::LiveRangeEdit::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### Remattable {#aad541aaf7fccb2c06d8b147fcd057e9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const VNInfo *, 4&gt; llvm::LiveRangeEdit::Remattable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remattable - Values defined by remattable instructions as identified by tii.isTriviallyReMaterializable().</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### Rematted {#a3d37aa2092d3093964d3aa17ed50d497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const VNInfo *, 4&gt; llvm::LiveRangeEdit::Rematted</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Rematted - Values that were actually rematted, and so need to have their live range trimmed or entirely removed.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### ScannedRemattable {#aa10b31e5a7652be9c07f9ab1a3bd2989}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveRangeEdit::ScannedRemattable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ScannedRemattable - true when remattable values have been identified.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### TheDelegate {#aebd1867695497f54607155afde4eb1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Delegate* const llvm::LiveRangeEdit::TheDelegate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### TII {#afd98603f84f326966c0270946fc00981}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; llvm::LiveRangeEdit::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

### VRM {#a746358dbbff06052d96c3c2266d59f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap* llvm::LiveRangeEdit::VRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/liverangeedit-h">LiveRangeEdit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeedit-cpp">LiveRangeEdit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
