---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/livevariables
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LiveVariables` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::LiveVariables { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">llvm/CodeGen/LiveVariables.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af677d960ef659b4136f39d9525ab9886">LiveVariablesWrapperPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94ed84d4e32ab0c0ce0aec69fb44310b">LiveVariables</a> (MachineFunction &amp;MF)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a963069aa63e5bfc6c4852d812768ddb6">LiveVariables</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78798d8de583a196655b3cfb347da991">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e0695dc8fb597f66ca702309da941f7">recomputeForSingleDefVirtReg</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recompute liveness from scratch for a virtual register <span class="doxyComputerOutput">Reg</span> that is known to have a single def that dominates all uses. <a href="#a9e0695dc8fb597f66ca702309da941f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007ef08997c0b0391aaebc27e257062c">replaceKillInstruction</a> (Register Reg, MachineInstr &amp;OldMI, MachineInstr &amp;NewMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>replaceKillInstruction - Update register kill info by replacing a kill instruction with a new one. <a href="#a007ef08997c0b0391aaebc27e257062c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58f90c0c07a77319dd769a8588a0fa7">addVirtualRegisterKilled</a> (Register IncomingReg, MachineInstr &amp;MI, bool AddIfNotFound=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addVirtualRegisterKilled - Add information about the fact that the specified register is killed after being used by the specified instruction. <a href="#ae58f90c0c07a77319dd769a8588a0fa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515b9b6464ec4cbf5133d51f63a4e489">removeVirtualRegisterKilled</a> (Register Reg, MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeVirtualRegisterKilled - Remove the specified kill of the virtual register from the live variable information. <a href="#a515b9b6464ec4cbf5133d51f63a4e489">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a536d28604beba413c49c1f731df008a7">removeVirtualRegistersKilled</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeVirtualRegistersKilled - Remove all killed info for the specified instruction. <a href="#a536d28604beba413c49c1f731df008a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a722a7eaa41e03a18392be831f831627d">addVirtualRegisterDead</a> (Register IncomingReg, MachineInstr &amp;MI, bool AddIfNotFound=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addVirtualRegisterDead - Add information about the fact that the specified register is dead after being used by the specified instruction. <a href="#a722a7eaa41e03a18392be831f831627d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ce32310fd2a5d6bf58316fd2a7ad1bf">removeVirtualRegisterDead</a> (Register Reg, MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removeVirtualRegisterDead - Remove the specified kill of the virtual register from the live variable information. <a href="#a3ce32310fd2a5d6bf58316fd2a7ad1bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getVarInfo - Return the <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> structure for the specified VIRTUAL register. <a href="#af73ca972d296b25a689a90fb5a0713f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a051cfe914c1c4eb2ceabb758d018a966">MarkVirtRegAliveInBlock</a> (VarInfo &amp;VRInfo, MachineBasicBlock *DefBlock, MachineBasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a296cf971c4bc03d1b469f52b687661db">MarkVirtRegAliveInBlock</a> (VarInfo &amp;VRInfo, MachineBasicBlock *DefBlock, MachineBasicBlock *BB, SmallVectorImpl&lt; MachineBasicBlock * &gt; &amp;WorkList)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7339056d25e6a6d7d1525f2ac0d1fe69">HandleVirtRegDef</a> (Register reg, MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e33b16879b183b0a9058363e2061de">HandleVirtRegUse</a> (Register reg, MachineBasicBlock *MBB, MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87536d29ad236f911a1e72dd210f9305">isLiveIn</a> (Register Reg, const MachineBasicBlock &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d2c1d51163472e4b2a332a954203e8">isLiveOut</a> (Register Reg, const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isLiveOut - Determine if Reg is live out from MBB, when not considering PHI nodes. <a href="#a72d2c1d51163472e4b2a332a954203e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbcff91139fc89e3e8c0dda857e7b128">addNewBlock</a> (MachineBasicBlock *BB, MachineBasicBlock *DomBB, MachineBasicBlock *SuccBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addNewBlock - Add a new basic block BB between DomBB and SuccBB. <a href="#afbcff91139fc89e3e8c0dda857e7b128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc347ae9e7fcba69b04162d7b4a73635">addNewBlock</a> (MachineBasicBlock *BB, MachineBasicBlock *DomBB, MachineBasicBlock *SuccBB, std::vector&lt; SparseBitVector&lt;&gt; &gt; &amp;LiveInSets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addNewBlock - Add a new basic block BB as an empty succcessor to DomBB. <a href="#afc347ae9e7fcba69b04162d7b4a73635">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac1d2c50b18f58b2929897562f207eb">analyze</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a133ad9385d9a0008cdb2f100e0ec5e37">HandlePhysRegKill</a> (Register Reg, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandlePhysRegKill - Add kills of Reg and its sub-registers to the uses. <a href="#a133ad9385d9a0008cdb2f100e0ec5e37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0279b88998c78e819fbd9a222da50ace">HandleRegMask</a> (const MachineOperand &amp;, unsigned)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandleRegMask - Call HandlePhysRegKill for all registers clobbered by Mask. <a href="#a0279b88998c78e819fbd9a222da50ace">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b42e472375a7fa90620c13c4fd0a9b">HandlePhysRegUse</a> (Register Reg, MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandlePhysRegUse - Turn previous partial def's into read/mod/writes. <a href="#ae8b42e472375a7fa90620c13c4fd0a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab940974b45461bf00693dc8866729993">HandlePhysRegDef</a> (Register Reg, MachineInstr *MI, SmallVectorImpl&lt; Register &gt; &amp;Defs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1817bf9defc3b7d9c4df376f1cc3b0">UpdatePhysRegDefs</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;Defs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d094ae7f9aaa3d2ce884ddf8b6c462">FindLastRefOrPartRef</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindLastRefOrPartRef - Return the last reference or partial reference of the specified register. <a href="#a53d094ae7f9aaa3d2ce884ddf8b6c462">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56fb23643cda6412e4b8c4ba93e5991a">FindLastPartialDef</a> (Register Reg, SmallSet&lt; Register, 4 &gt; &amp;PartDefRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindLastPartialDef - Return the last partial def of the specified register. <a href="#a56fb23643cda6412e4b8c4ba93e5991a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a464b62dd1024f8a8f579fc29fed6edec">analyzePHINodes</a> (const MachineFunction &amp;Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>analyzePHINodes - Gather information about the PHI nodes in here. <a href="#a464b62dd1024f8a8f579fc29fed6edec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4717b484807064e284ce5415f52b1ab">runOnInstr</a> (MachineInstr &amp;MI, SmallVectorImpl&lt; Register &gt; &amp;Defs, unsigned NumRegs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf332f596c5a04cbe79b63b486f5a3dc">runOnBlock</a> (MachineBasicBlock *MBB, unsigned NumRegs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d970feb51d0ee8670c5da391f533f94">VirtRegInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/virtreginfo">VirtRegInfo</a> - This list is a mapping from virtual register number to variable information. <a href="#a6d970feb51d0ee8670c5da391f533f94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac308cef0f801c7f2701a75c511268c10">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb59e342d9d5fcbdc581bb0ea86693dd">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d565b4674f1c4f1fde45f9ec23afa1">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a536eba5bba27729f3892ee9ab728e15a">PhysRegDef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a816f0ca300d708e6e7af43693e231406">PhysRegUse</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2691615f402979e6a169b0f90d1f38">PHIVarInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd96b92005bcae18721f99818523d73">DistanceMap</a></td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<div class="doxySectionDef">

## Friends

### LiveVariablesWrapperPass {#af677d960ef659b4136f39d9525ab9886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/livevariableswrapperpass">LiveVariablesWrapperPass</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>Reference <a href="#af677d960ef659b4136f39d9525ab9886">LiveVariablesWrapperPass</a>.</p>


<p>Referenced by <a href="#af677d960ef659b4136f39d9525ab9886">LiveVariablesWrapperPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### LiveVariables() {#a94ed84d4e32ab0c0ce0aec69fb44310b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveVariables::LiveVariables (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### LiveVariables() {#a963069aa63e5bfc6c4852d812768ddb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LiveVariables::LiveVariables ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addNewBlock() {#afbcff91139fc89e3e8c0dda857e7b128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::addNewBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DomBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addNewBlock - Add a new basic block BB between DomBB and SuccBB.</p>


<p>addNewBlock - Add a new basic block BB as an empty succcessor to DomBB.</p>


<p>All variables that are live out of DomBB and live into SuccBB will be marked as passing live through BB. This method assumes that the machine code is still in SSA form.</p>


<p>All variables that are live out of DomBB will be marked as passing live through BB.</p>


<p>Declaration at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 850 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a76321b20db4feab750d85c2329cfcbc6">llvm::LiveVariables::VarInfo::AliveBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#afe504aa31a6a354cec13f5b32d0b1d9d">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a613c1e44c4e88e9a1e0be386cb5fa828">llvm::SparseBitVector&lt; ElementSize &gt;::set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### addNewBlock() {#afc347ae9e7fcba69b04162d7b4a73635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::addNewBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DomBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * SuccBB, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector">SparseBitVector</a>&lt;&gt; &gt; &amp; LiveInSets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addNewBlock - Add a new basic block BB as an empty succcessor to DomBB.</p>


<p>All variables that are live out of DomBB will be marked as passing live through BB. LiveInSets[BB] is <em>not</em> updated (because it is not needed during PHIElimination).</p>


<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a76321b20db4feab750d85c2329cfcbc6">llvm::LiveVariables::VarInfo::AliveBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a> and <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a613c1e44c4e88e9a1e0be386cb5fa828">llvm::SparseBitVector&lt; ElementSize &gt;::set</a>.</p>

</div>
</div>

### addVirtualRegisterDead() {#a722a7eaa41e03a18392be831f831627d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveVariables::addVirtualRegisterDead (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> IncomingReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool AddIfNotFound=false)</td>
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

<p>addVirtualRegisterDead - Add information about the fact that the specified register is dead after being used by the specified instruction.</p>


<p>If AddIfNotFound is true, add a implicit operand if it's not found.</p>


<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>References <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a65c816771eca7465f5e3e0bb6624ad88">llvm::LiveVariables::VarInfo::Kills</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### addVirtualRegisterKilled() {#ae58f90c0c07a77319dd769a8588a0fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LiveVariables::addVirtualRegisterKilled (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> IncomingReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, bool AddIfNotFound=false)</td>
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

<p>addVirtualRegisterKilled - Add information about the fact that the specified register is killed after being used by the specified instruction.</p>


<p>If AddIfNotFound is true, add a implicit operand if it's not found.</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>References <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a65c816771eca7465f5e3e0bb6624ad88">llvm::LiveVariables::VarInfo::Kills</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>.</p>

</div>
</div>

### getVarInfo() {#af73ca972d296b25a689a90fb5a0713f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveVariables::VarInfo &amp; LiveVariables::getVarInfo (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getVarInfo - Return the <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> structure for the specified VIRTUAL register.</p>


<p>getVarInfo - Get (possibly creating) a <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> object for the given vreg.</p>


<p>Declaration at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#afbcff91139fc89e3e8c0dda857e7b128">addNewBlock</a>, <a href="#afc347ae9e7fcba69b04162d7b4a73635">addNewBlock</a>, <a href="#a722a7eaa41e03a18392be831f831627d">addVirtualRegisterDead</a>, <a href="#ae58f90c0c07a77319dd769a8588a0fa7">addVirtualRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aa264594513bbe667a36f2a0609fd0b3f">llvm::ARMBaseInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ad4445a2ce5876c120e2a6e6796edaf5c">llvm::SIInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a>, <a href="#a7339056d25e6a6d7d1525f2ac0d1fe69">HandleVirtRegDef</a>, <a href="#ac7e33b16879b183b0a9058363e2061de">HandleVirtRegUse</a>, <a href="#a87536d29ad236f911a1e72dd210f9305">isLiveIn</a>, <a href="#a72d2c1d51163472e4b2a332a954203e8">isLiveOut</a>, <a href="#a9e0695dc8fb597f66ca702309da941f7">recomputeForSingleDefVirtReg</a>, <a href="#a3ce32310fd2a5d6bf58316fd2a7ad1bf">removeVirtualRegisterDead</a>, <a href="#a515b9b6464ec4cbf5133d51f63a4e489">removeVirtualRegisterKilled</a>, <a href="#a536d28604beba413c49c1f731df008a7">removeVirtualRegistersKilled</a>, <a href="#a007ef08997c0b0391aaebc27e257062c">replaceKillInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>.</p>

</div>
</div>

### HandleVirtRegDef() {#a7339056d25e6a6d7d1525f2ac0d1fe69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::HandleVirtRegDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a76321b20db4feab750d85c2329cfcbc6">llvm::LiveVariables::VarInfo::AliveBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#af3b1d1c23a2507b717c7a9acc0d5ae49">llvm::SparseBitVector&lt; ElementSize &gt;::empty</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a65c816771eca7465f5e3e0bb6624ad88">llvm::LiveVariables::VarInfo::Kills</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### HandleVirtRegUse() {#ac7e33b16879b183b0a9058363e2061de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::HandleVirtRegUse (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a76321b20db4feab750d85c2329cfcbc6">llvm::LiveVariables::VarInfo::AliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a65c816771eca7465f5e3e0bb6624ad88">llvm::LiveVariables::VarInfo::Kills</a>, <a href="#a051cfe914c1c4eb2ceabb758d018a966">MarkVirtRegAliveInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#aaa2827e67554a0b81f693dc61a3a40b5">llvm::SparseBitVector&lt; ElementSize &gt;::test</a>.</p>

</div>
</div>

### isLiveIn() {#a87536d29ad236f911a1e72dd210f9305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveVariables::isLiveIn (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>References <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#ade24291007dd6f2b3c90c4323499d7eb">llvm::LiveVariables::VarInfo::isLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### isLiveOut() {#a72d2c1d51163472e4b2a332a954203e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveVariables::isLiveOut (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isLiveOut - Determine if Reg is live out from MBB, when not considering PHI nodes.</p>


<p>This means that Reg is either killed by a successor block or passed through one.</p>


<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### MarkVirtRegAliveInBlock() {#a051cfe914c1c4eb2ceabb758d018a966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::MarkVirtRegAliveInBlock (<a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> &amp; VRInfo, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DefBlock, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a051cfe914c1c4eb2ceabb758d018a966">MarkVirtRegAliveInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>.</p>


<p>Referenced by <a href="#ac7e33b16879b183b0a9058363e2061de">HandleVirtRegUse</a> and <a href="#a051cfe914c1c4eb2ceabb758d018a966">MarkVirtRegAliveInBlock</a>.</p>

</div>
</div>

### MarkVirtRegAliveInBlock() {#a296cf971c4bc03d1b469f52b687661db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::MarkVirtRegAliveInBlock (<a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo">VarInfo</a> &amp; VRInfo, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * DefBlock, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; WorkList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a76321b20db4feab750d85c2329cfcbc6">llvm::LiveVariables::VarInfo::AliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a65c816771eca7465f5e3e0bb6624ad88">llvm::LiveVariables::VarInfo::Kills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a613c1e44c4e88e9a1e0be386cb5fa828">llvm::SparseBitVector&lt; ElementSize &gt;::set</a> and <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#aaa2827e67554a0b81f693dc61a3a40b5">llvm::SparseBitVector&lt; ElementSize &gt;::test</a>.</p>

</div>
</div>

### print() {#a78798d8de583a196655b3cfb347da991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a578f01f3e0679351d97facbba44c583e">llvm::LiveVariables::VarInfo::dump</a>.</p>

</div>
</div>

### recomputeForSingleDefVirtReg() {#a9e0695dc8fb597f66ca702309da941f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::recomputeForSingleDefVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recompute liveness from scratch for a virtual register <span class="doxyComputerOutput">Reg</span> that is known to have a single def that dominates all uses.</p>


<p>This can be useful after removing some uses of <span class="doxyComputerOutput">Reg</span>. It is not necessary for the whole machine function to be in SSA form.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab644fcf07a4c2708333cf66276282357">llvm::MachineBasicBlock::pred_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a0359a738e0412c5a7ea55d61175e0661">llvm::MachineBasicBlock::pred_end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsebitvector/#a613c1e44c4e88e9a1e0be386cb5fa828">llvm::SparseBitVector&lt; ElementSize &gt;::set</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62a1e2af50ab6132cd2d8d168835ef57">llvm::PPCInstrInfo::promoteInstr32To64ForElimEXTSW</a>.</p>

</div>
</div>

### removeVirtualRegisterDead() {#a3ce32310fd2a5d6bf58316fd2a7ad1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveVariables::removeVirtualRegisterDead (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>removeVirtualRegisterDead - Remove the specified kill of the virtual register from the live variable information.</p>


<p>Returns true if the variable was marked dead at the specified instruction, false otherwise.</p>


<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### removeVirtualRegisterKilled() {#a515b9b6464ec4cbf5133d51f63a4e489}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LiveVariables::removeVirtualRegisterKilled (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>removeVirtualRegisterKilled - Remove the specified kill of the virtual register from the live variable information.</p>


<p>Returns true if the variable was marked as killed by the specified instruction, false otherwise.</p>


<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### removeVirtualRegistersKilled() {#a536d28604beba413c49c1f731df008a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::removeVirtualRegistersKilled (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>removeVirtualRegistersKilled - Remove all killed info for the specified instruction.</p>

<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 778 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4046212ebc647b17e811837ae4ea3afd">llvm::MachineOperand::isKill</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a1e808b535590177bb00545b77a324288">llvm::LiveVariables::VarInfo::removeKill</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>.</p>

</div>
</div>

### replaceKillInstruction() {#a007ef08997c0b0391aaebc27e257062c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::replaceKillInstruction (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; OldMI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; NewMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>replaceKillInstruction - Update register kill info by replacing a kill instruction with a new one.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>


<p>Reference <a href="#af73ca972d296b25a689a90fb5a0713f3">getVarInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#acf40b35a88eb365bc4f4047a03bb1ece">llvm::X86InstrInfo::classifyLEAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a061f47e0bf17eed5f4fb190668a20858">llvm::RISCVInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#a414af156e6dae8024f5321babf41afb2">llvm::SystemZInstrInfo::convertToThreeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a57da368572a9e56d7a211cc8e12581d7">llvm::X86InstrInfo::convertToThreeAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a8edb2219f51b89b23621bd1da1dfd6f8">updateLiveVariables</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### analyze() {#a5ac1d2c50b18f58b2929897562f207eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::analyze (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### analyzePHINodes() {#a464b62dd1024f8a8f579fc29fed6edec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::analyzePHINodes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>analyzePHINodes - Gather information about the PHI nodes in here.</p>


<p>In particular, we want to map the variable information of a virtual register which is used in a PHI node. We map that to the BB the vreg is coming from.</p>


<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### FindLastPartialDef() {#a56fb23643cda6412e4b8c4ba93e5991a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * LiveVariables::FindLastPartialDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt; &amp; PartDefRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FindLastPartialDef - Return the last partial def of the specified register.</p>


<p>Also returns the sub-registers that're defined by the instruction.</p>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### FindLastRefOrPartRef() {#a53d094ae7f9aaa3d2ce884ddf8b6c462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * LiveVariables::FindLastRefOrPartRef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FindLastRefOrPartRef - Return the last reference or partial reference of the specified register.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### HandlePhysRegDef() {#ab940974b45461bf00693dc8866729993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::HandlePhysRegDef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### HandlePhysRegKill() {#a133ad9385d9a0008cdb2f100e0ec5e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LiveVariables::HandlePhysRegKill (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HandlePhysRegKill - Add kills of Reg and its sub-registers to the uses.</p>


<p>Pay special attention to the sub-register uses which may come below the last use of the whole register.</p>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### HandlePhysRegUse() {#ae8b42e472375a7fa90620c13c4fd0a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::HandlePhysRegUse (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HandlePhysRegUse - Turn previous partial def's into read/mod/writes.</p>


<p>Add implicit defs to a machine instruction if there was an earlier def of its super-register.</p>


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### HandleRegMask() {#a0279b88998c78e819fbd9a222da50ace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::HandleRegMask (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, unsigned NumRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HandleRegMask - Call HandlePhysRegKill for all registers clobbered by Mask.</p>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### runOnBlock() {#aaf332f596c5a04cbe79b63b486f5a3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::runOnBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, unsigned NumRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### runOnInstr() {#ad4717b484807064e284ce5415f52b1ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::runOnInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Defs, unsigned NumRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 512 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

### UpdatePhysRegDefs() {#aef1817bf9defc3b7d9c4df376f1cc3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveVariables::UpdatePhysRegDefs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DistanceMap {#addd96b92005bcae18721f99818523d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr*, unsigned&gt; llvm::LiveVariables::DistanceMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### MF {#ac308cef0f801c7f2701a75c511268c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::LiveVariables::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### MRI {#abb59e342d9d5fcbdc581bb0ea86693dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::LiveVariables::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### PHIVarInfo {#afc2691615f402979e6a169b0f90d1f38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SmallVector&lt;unsigned, 4&gt; &gt; llvm::LiveVariables::PHIVarInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### PhysRegDef {#a536eba5bba27729f3892ee9ab728e15a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr *&gt; llvm::LiveVariables::PhysRegDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### PhysRegUse {#a816f0ca300d708e6e7af43693e231406}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineInstr *&gt; llvm::LiveVariables::PhysRegUse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### TRI {#ad2d565b4674f1c4f1fde45f9ec23afa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::LiveVariables::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

### VirtRegInfo {#a6d970feb51d0ee8670c5da391f533f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;VarInfo, VirtReg2IndexFunctor&gt; llvm::LiveVariables::VirtRegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/virtreginfo">VirtRegInfo</a> - This list is a mapping from virtual register number to variable information.</p>

<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livevariables-h">LiveVariables.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/livevariables-cpp">LiveVariables.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
