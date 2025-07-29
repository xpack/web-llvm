---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlinespiller-cpp-/inlinespiller
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InlineSpiller` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{InlineSpiller.cpp}::InlineSpiller { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/spiller">Spiller</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/spiller">Spiller</a> interface. <a href="/web-llvm/docs/api/classes/llvm/spiller/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0c7217cff94684e7fc187430202840">InlineSpiller</a> (const Spiller::RequiredAnalyses &amp;Analyses, MachineFunction &amp;MF, VirtRegMap &amp;VRM, VirtRegAuxInfo &amp;VRAI)</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d5b9653292e15a2c4757e968f59a3dc">~InlineSpiller</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74cc1b6ed58474b37bafc059339a964">spill</a> (LiveRangeEdit &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spill - Spill the LRE.getParent() live interval. <a href="#af74cc1b6ed58474b37bafc059339a964">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba96a5852ccf89d884e544402982c64">getSpilledRegs</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the registers that were spilled. <a href="#a5ba96a5852ccf89d884e544402982c64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a8cfa439b882ecb77934b91f0058197">getReplacedRegs</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return registers that were not spilled, but otherwise replaced (e.g. <a href="#a6a8cfa439b882ecb77934b91f0058197">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0f0b88f27ccdcc4df2f11d07f2bc5e">postOptimization</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimizations after all the reg selections and spills are done. <a href="#a5c0f0b88f27ccdcc4df2f11d07f2bc5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a67c2c96c59bbb77715695ea841c7c">isSnippet</a> (const LiveInterval &amp;SnipLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isSnippet - Identify if a live interval is a snippet that should be spilled. <a href="#a72a67c2c96c59bbb77715695ea841c7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3059b439fade3e7d242091a626ee61c">collectRegsToSpill</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>collectRegsToSpill - Collect live range snippets that only have a single real use. <a href="#ad3059b439fade3e7d242091a626ee61c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af93c14ce936f649c638cc93689e5f852">isRegToSpill</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb0de636cb5d4a8c224de27166691de">isSibling</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e52cad48ef33aa3ad8dc031b815f25">hoistSpillInsideBB</a> (LiveInterval &amp;SpillLI, MachineInstr &amp;CopyMI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It is beneficial to spill to earlier place in the same BB in case as follows: There is an alternative def earlier in the same MBB. <a href="#ac8e52cad48ef33aa3ad8dc031b815f25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b5ced3c3b549d5cdfa23ffb7d7ee3d">eliminateRedundantSpills</a> (LiveInterval &amp;LI, VNInfo *VNI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>eliminateRedundantSpills - SLI:VNI is known to be on the stack. <a href="#a44b5ced3c3b549d5cdfa23ffb7d7ee3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae498641a03e87b896d592ee384e9641c">markValueUsed</a> (LiveInterval *, VNInfo *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>markValueUsed - Remember that VNI failed to rematerialize, so its defining instruction cannot be eliminated. <a href="#ae498641a03e87b896d592ee384e9641c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae7f7a6e222109ad7ac4493cea8a9d7">canGuaranteeAssignmentAfterRemat</a> (Register VReg, MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7010104d90c189215655c3171138d78e">reMaterializeFor</a> (LiveInterval &amp;, MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reMaterializeFor - Attempt to rematerialize before MI instead of reloading. <a href="#a7010104d90c189215655c3171138d78e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5c7996991dbd8fa72fc9021e773c0f">reMaterializeAll</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reMaterializeAll - Try to rematerialize as many uses as possible, and trim the live ranges after. <a href="#a2d5c7996991dbd8fa72fc9021e773c0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bf1d80315608c18cb5c2fecce23b5c0">coalesceStackAccess</a> (MachineInstr *MI, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If MI is a load or store of StackSlot, it can be removed. <a href="#a2bf1d80315608c18cb5c2fecce23b5c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ab13e22ad3aaecd2bf4292dfd6a124">foldMemoryOperand</a> (ArrayRef&lt; std::pair&lt; MachineInstr *, unsigned &gt; &gt;, MachineInstr *LoadMI=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>foldMemoryOperand - Try folding stack slot references in Ops into their instructions. <a href="#a33ab13e22ad3aaecd2bf4292dfd6a124">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a8372bd6497ed748ef4785cbaf19461">insertReload</a> (Register VReg, SlotIndex, MachineBasicBlock::iterator MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdf2a84d8c95eb189dc2204a0d5ddda3">insertSpill</a> (Register VReg, bool isKill, MachineBasicBlock::iterator MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>insertSpill - Insert a spill of NewVReg after MI. <a href="#afdf2a84d8c95eb189dc2204a0d5ddda3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6749219533bcffac22ca9486085196">spillAroundUses</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillAroundUses - insert spill code around each use of Reg. <a href="#adc6749219533bcffac22ca9486085196">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40f4001228f14abde024aee59ba91413">spillAll</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>spillAll - Spill all registers remaining after rematerialization. <a href="#a40f4001228f14abde024aee59ba91413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25feb03943caf417a2469dad45e50c0a">MF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a984a8b49492577c585e0f4ce098f245f">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livestacks">LiveStacks</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea3e30a40ec864252749221937e9ba5">LSS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab678ed97e9cab5332dc783b7196945a1">VRM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1806ae9d7bbc077d6c00038a20dbdae1">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ab9189bc53ab5bfc100fcf8346f357">TII</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5c7900e89ae5ce23c834db892f2a54">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a077eedc983f7f0f8e773aea26bea5826">Edit</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd12b67a1e3249536ffc0bec44781fb">StackInt</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d411755525f771a15dbc24fe87b75ec">StackSlot</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e29372988a6182b57e6362e227a156d">Original</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bbf63c52438ce7167db9ec2eea35cd9">RegsToSpill</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09adc6c32169740bac1dc18be02b785d">RegsReplaced</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9aecedfb99dbdd57792f5eb4bd9cca0">SnippetCopies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b999e5775f41de23699ff7cf5a15855">UsedValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaf9e0bce1a80743d624f9c412203b78">DeadDefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper">HoistSpillHelper</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da9c654f6a51be2cea3c3063cd8d9fe">HSpiller</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo">VirtRegAuxInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f22e82cc9314da174c905b0874d988d">VRAI</a></td>
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


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InlineSpiller() {#acf0c7217cff94684e7fc187430202840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineSpiller.cpp}::InlineSpiller::InlineSpiller (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/spiller/requiredanalyses">Spiller::RequiredAnalyses</a> &amp; Analyses, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; VRM, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo">VirtRegAuxInfo</a> &amp; VRAI)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~InlineSpiller() {#a1d5b9653292e15a2c4757e968f59a3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineSpiller.cpp}::InlineSpiller::~InlineSpiller ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getReplacedRegs() {#a6a8cfa439b882ecb77934b91f0058197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Register &gt; anonymous{InlineSpiller.cpp}::InlineSpiller::getReplacedRegs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return registers that were not spilled, but otherwise replaced (e.g.</p>


<p>rematerialized).</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### getSpilledRegs() {#a5ba96a5852ccf89d884e544402982c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Register &gt; anonymous{InlineSpiller.cpp}::InlineSpiller::getSpilledRegs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the registers that were spilled.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### postOptimization() {#a5c0f0b88f27ccdcc4df2f11d07f2bc5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::postOptimization ()</td>
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

<p>Optimizations after all the reg selections and spills are done.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### spill() {#af74cc1b6ed58474b37bafc059339a964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::spill (<a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> &amp; LRE)</td>
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

<p>spill - Spill the LRE.getParent() live interval.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#a989ed5e9a7610a873a79ea663f83b814">llvm::LiveRangeEdit::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#ac2d157d94da9ea6da55d19a1fa8d9247">llvm::LiveRangeEdit::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a1a07a284547e2997c90a6a1be428cd47">llvm::LiveInterval::isSpillable</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a050c8e969ce1fa8c229b074fd07be925">llvm::Register::isStackSlot</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canGuaranteeAssignmentAfterRemat() {#a0ae7f7a6e222109ad7ac4493cea8a9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::canGuaranteeAssignmentAfterRemat (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### coalesceStackAccess() {#a2bf1d80315608c18cb5c2fecce23b5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::coalesceStackAccess (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If MI is a load or store of StackSlot, it can be removed.</p>

<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### collectRegsToSpill() {#ad3059b439fade3e7d242091a626ee61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::collectRegsToSpill ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>collectRegsToSpill - Collect live range snippets that only have a single real use.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### eliminateRedundantSpills() {#a44b5ced3c3b549d5cdfa23ffb7d7ee3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::eliminateRedundantSpills (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; SLI, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>eliminateRedundantSpills - SLI:VNI is known to be on the stack.</p>


<p>Remove any redundant spills of this value in SLI.reg and sibling copies.</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### foldMemoryOperand() {#a33ab13e22ad3aaecd2bf4292dfd6a124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::foldMemoryOperand (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt; &gt; Ops, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * LoadMI=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>foldMemoryOperand - Try folding stack slot references in Ops into their instructions.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ops</td>
<td class="doxyParamItemDescription"><p>Operand indices from <a href="/web-llvm/docs/api/namespaces/llvm/#a9497f45131416e6d7d716221c3deee8c">AnalyzeVirtRegInBundle()</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LoadMI</td>
<td class="doxyParamItemDescription"><p>Load instruction to use instead of stack slot when non-null.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on success.</p></dd>
</dl>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### hoistSpillInsideBB() {#ac8e52cad48ef33aa3ad8dc031b815f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::hoistSpillInsideBB (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; SpillLI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; CopyMI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It is beneficial to spill to earlier place in the same BB in case as follows: There is an alternative def earlier in the same MBB.</p>


<p>Hoist the spill as far as possible in SpillMBB. This can ease register pressure:</p>


<p>x = def y = use x s = copy x</p>


<p>Hoisting the spill of s to immediately after the def removes the interference between x and y:</p>


<p>x = def spill x y = use killed x</p>


<p>This hoist only helps when the copy kills its source.</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### insertReload() {#a5a8372bd6497ed748ef4785cbaf19461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::insertReload (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, <a href="/web-llvm/docs/api/classes/llvm/slotindex">SlotIndex</a> Idx, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### insertSpill() {#afdf2a84d8c95eb189dc2204a0d5ddda3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::insertSpill (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VReg, bool isKill, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>insertSpill - Insert a spill of NewVReg after MI.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### isRegToSpill() {#af93c14ce936f649c638cc93689e5f852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{InlineSpiller.cpp}::InlineSpiller::isRegToSpill (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### isSibling() {#a2bb0de636cb5d4a8c224de27166691de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::isSibling (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### isSnippet() {#a72a67c2c96c59bbb77715695ea841c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::isSnippet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; SnipLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isSnippet - Identify if a live interval is a snippet that should be spilled.</p>


<p>It is assumed that SnipLI is a virtual register with the same original as Edit-&gt;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg()</a>.</p>


<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### markValueUsed() {#ae498641a03e87b896d592ee384e9641c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::markValueUsed (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> * LI, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * VNI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>markValueUsed - Remember that VNI failed to rematerialize, so its defining instruction cannot be eliminated.</p>


<p>See through snippet copies</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### reMaterializeAll() {#a2d5c7996991dbd8fa72fc9021e773c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::reMaterializeAll ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reMaterializeAll - Try to rematerialize as many uses as possible, and trim the live ranges after.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### reMaterializeFor() {#a7010104d90c189215655c3171138d78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineSpiller::reMaterializeFor (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; VirtReg, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reMaterializeFor - Attempt to rematerialize before MI instead of reloading.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### spillAll() {#a40f4001228f14abde024aee59ba91413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::spillAll ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>spillAll - Spill all registers remaining after rematerialization.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### spillAroundUses() {#adc6749219533bcffac22ca9486085196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineSpiller::spillAroundUses (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>spillAroundUses - insert spill code around each use of Reg.</p>

<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DeadDefs {#aaaf9e0bce1a80743d624f9c412203b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 8&gt; anonymous{InlineSpiller.cpp}::InlineSpiller::DeadDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### Edit {#a077eedc983f7f0f8e773aea26bea5826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRangeEdit* anonymous{InlineSpiller.cpp}::InlineSpiller::Edit = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### HSpiller {#a6da9c654f6a51be2cea3c3063cd8d9fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HoistSpillHelper anonymous{InlineSpiller.cpp}::InlineSpiller::HSpiller</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### LIS {#a984a8b49492577c585e0f4ce098f245f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### LSS {#a3ea3e30a40ec864252749221937e9ba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveStacks&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::LSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MF {#a25feb03943caf417a2469dad45e50c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MRI {#a1806ae9d7bbc077d6c00038a20dbdae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### Original {#a2e29372988a6182b57e6362e227a156d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register anonymous{InlineSpiller.cpp}::InlineSpiller::Original</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### RegsReplaced {#a09adc6c32169740bac1dc18be02b785d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 8&gt; anonymous{InlineSpiller.cpp}::InlineSpiller::RegsReplaced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### RegsToSpill {#a6bbf63c52438ce7167db9ec2eea35cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 8&gt; anonymous{InlineSpiller.cpp}::InlineSpiller::RegsToSpill</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### SnippetCopies {#ad9aecedfb99dbdd57792f5eb4bd9cca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;MachineInstr*, 8&gt; anonymous{InlineSpiller.cpp}::InlineSpiller::SnippetCopies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### StackInt {#a5dd12b67a1e3249536ffc0bec44781fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveInterval* anonymous{InlineSpiller.cpp}::InlineSpiller::StackInt = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### StackSlot {#a0d411755525f771a15dbc24fe87b75ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{InlineSpiller.cpp}::InlineSpiller::StackSlot</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### TII {#a34ab9189bc53ab5bfc100fcf8346f357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### TRI {#a4e5c7900e89ae5ce23c834db892f2a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### UsedValues {#a5b999e5775f41de23699ff7cf5a15855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;VNInfo*, 8&gt; anonymous{InlineSpiller.cpp}::InlineSpiller::UsedValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### VRAI {#a5f22e82cc9314da174c905b0874d988d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegAuxInfo&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::VRAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### VRM {#ab678ed97e9cab5332dc783b7196945a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap&amp; anonymous{InlineSpiller.cpp}::InlineSpiller::VRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
