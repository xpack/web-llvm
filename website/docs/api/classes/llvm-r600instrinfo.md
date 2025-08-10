---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/r600instrinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `R600InstrInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::R600InstrInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">Target/AMDGPU/R600InstrInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/r600geninstrinfo">R600GenInstrInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BankSwizzle { <a href="#a684a33b88b11aeed1300272bb4cf9f73">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6b4a34f38efcec5ce770e58c69220f">R600InstrInfo</a> (const R600Subtarget &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo">R600RegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161e7f13bb4970a80ac16e93a7ebee73">getRegisterInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae780082016f8641ba5a18009b135d01e">copyPhysReg</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL, MCRegister DestReg, MCRegister SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50503e8c79cfae86f42c25b30c4dee2d">isLegalToSplitMBBAt</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f44398d0ba1f70349d99b68940febde">isReductionOp</a> (unsigned opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891797e1ad8f29e9ed5d3443f10dc82e">isCubeOp</a> (unsigned opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80e1e5645d57c506cb63732f576ce81">isALUInstr</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1215beb8e209f4246f9809770be405d9">hasInstrModifiers</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89de148c8666da38bdf2b414f9e254ec">isLDSInstr</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab64e90b1e671bf82b2dbcc831d63ddbf">isLDSRetInstr</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507703ee09a583ff911a8d09cd409b68">canBeConsideredALU</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3de1aca767b960a302308f3c463317">isTransOnly</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4040056c150bccdd7d14849ffa9486d">isTransOnly</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb5663da5534317c035227ab390bf36">isVectorOnly</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa7e2ed9eabcb9cc26a590209d53d9d">isVectorOnly</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add24e1463a36a613e008ed84227b4785">isExport</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0220f9eee026db654316584948dede8d">usesVertexCache</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbae172c51615eb52ec12f0af642de64">usesVertexCache</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a26ade8a5837be3ac8373a6edc81350">usesTextureCache</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a228e67ed635dc4282489be7f3fc1c2e8">usesTextureCache</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6051ea915d00d989d449bb69ab996d4b">mustBeLastInClause</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0aa3d48f55eef628d97bb21156177f19">usesAddressRegister</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f981149d5958196da00178c5640d576">definesAddressRegister</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbfbaa0e925b1f975b016053d752e899">readsLDSSrcReg</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab858beae728e107227a9e07759588087">getSelIdx</a> (unsigned Opcode, unsigned SrcIdx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> *, int64_t &gt;, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6f1cb7931164d888acd081fa41e6246">getSrcs</a> (MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fce8516b6f35622360433c3bae2b70c">isLegalUpTo</a> (const std::vector&lt; std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &gt; &amp;IGSrcs, const std::vector&lt; R600InstrInfo::BankSwizzle &gt; &amp;Swz, const std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &amp;TransSrcs, R600InstrInfo::BankSwizzle TransSwz) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns how many MIs (whose inputs are represented by IGSrcs) can be packed in the same <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Group while meeting read port limitations given a Swz swizzle sequence. <a href="#a2fce8516b6f35622360433c3bae2b70c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accae71a18e9054f96a7919785976ee15">FindSwizzleForVectorSlot</a> (const std::vector&lt; std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &gt; &amp;IGSrcs, std::vector&lt; R600InstrInfo::BankSwizzle &gt; &amp;SwzCandidate, const std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &amp;TransSrcs, R600InstrInfo::BankSwizzle TransSwz) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerate all possible Swizzle sequence to find one that can meet all read port requirements. <a href="#accae71a18e9054f96a7919785976ee15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4bc494da88251a58ca644dec0d15a2e">fitsReadPortLimitations</a> (const std::vector&lt; MachineInstr * &gt; &amp;MIs, const DenseMap&lt; unsigned, unsigned &gt; &amp;PV, std::vector&lt; BankSwizzle &gt; &amp;BS, bool isLastAluTrans) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given the order VEC_012 &lt; VEC_021 &lt; VEC_120 &lt; VEC_102 &lt; VEC_201 &lt; VEC_210 returns true and the first (in lexical order) <a href="#a684a33b88b11aeed1300272bb4cf9f73">BankSwizzle</a> affectation starting from the one already provided in the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Group MIs that fits Read Port limitations in BS if available. <a href="#ad4bc494da88251a58ca644dec0d15a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a537788ca2a4d7bbdbfad2ac8e5dfabca">fitsConstReadLimitations</a> (const std::vector&lt; MachineInstr * &gt; &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction group can only access 2 channel pair (either [XY] or [ZW]) from KCache bank on R700+. <a href="#a537788ca2a4d7bbdbfad2ac8e5dfabca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2602638ef43bcf2b073625f2bd0d9c8">fitsConstReadLimitations</a> (const std::vector&lt; unsigned &gt; &amp;) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same but using const index set instead of MI set. <a href="#ad2602638ef43bcf2b073625f2bd0d9c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bad3393698345347bc9ef02419fd8cd">isVector</a> (const MachineInstr &amp;MI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Vector instructions are instructions that must fill all instruction slots within an instruction group. <a href="#a5bad3393698345347bc9ef02419fd8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fddf85baa47d23103126f2a45ea3a4e">isMov</a> (unsigned Opcode) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e6aef88dec63b3e87ab2a3fc6f9c78">CreateTargetScheduleState</a> (const TargetSubtargetInfo &amp;) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c6876ed7ada0d971240509db503dc0">reverseBranchCondition</a> (SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086f43049b2d52208b7727be22f5e604">analyzeBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *&amp;TBB, MachineBasicBlock *&amp;FBB, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, bool AllowModify) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648e69f41d62376b996b0b5209022fbd">insertBranch</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock *TBB, MachineBasicBlock *FBB, ArrayRef&lt; MachineOperand &gt; Cond, const DebugLoc &amp;DL, int *BytesAdded=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c764241e49b1b62cbe5153f384ef196">removeBranch</a> (MachineBasicBlock &amp;MBB, int *BytesRemoved=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab39a8eb989f01d8ed539a6fe6a210ba6">isPredicated</a> (const MachineInstr &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab334b6a433595c3b14311e50ed433119">isPredicable</a> (const MachineInstr &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2700054a144dc843858ac4954f53e2b4">isProfitableToDupForIfCvt</a> (MachineBasicBlock &amp;MBB, unsigned NumCycles, BranchProbability Probability) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83513847e40eb20946e50e05d50fc3b">isProfitableToIfCvt</a> (MachineBasicBlock &amp;MBB, unsigned NumCycles, unsigned ExtraPredCycles, BranchProbability Probability) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49fa0640f041ac13c4f7d6eacf03278b">isProfitableToIfCvt</a> (MachineBasicBlock &amp;TMBB, unsigned NumTCycles, unsigned ExtraTCycles, MachineBasicBlock &amp;FMBB, unsigned NumFCycles, unsigned ExtraFCycles, BranchProbability Probability) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70329ea652d85d2cdc7095f7ad9c453">ClobbersPredicate</a> (MachineInstr &amp;MI, std::vector&lt; MachineOperand &gt; &amp;Pred, bool SkipDead) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508277c4ff138f71ec87b10f00063586">isProfitableToUnpredicate</a> (MachineBasicBlock &amp;TMBB, MachineBasicBlock &amp;FMBB) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4501178e61d2f154d7b9bc4fc519fe68">PredicateInstruction</a> (MachineInstr &amp;MI, ArrayRef&lt; MachineOperand &gt; Pred) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39a8558f3e2c9d7806eab38a2bc3fa6">getPredicationCost</a> (const MachineInstr &amp;) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3317ad36612bd0a93dad2af012182dc7">getInstrLatency</a> (const InstrItineraryData *ItinData, const MachineInstr &amp;MI, unsigned *PredCost=nullptr) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c95ecc60411327fd2f6c5d0664224c">expandPostRAPseudo</a> (MachineInstr &amp;MI) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa21fe05557eb564cf547a20ccf43d9f5">reserveIndirectRegisters</a> (BitVector &amp;Reserved, const MachineFunction &amp;MF, const R600RegisterInfo &amp;TRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve the registers that may be accessed using indirect addressing. <a href="#aa21fe05557eb564cf547a20ccf43d9f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd21a3c7db6ec5b26c776c6b5fe4b13">calculateIndirectAddress</a> (unsigned RegIndex, unsigned Channel) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the "Indirect Address" for the given <span class="doxyComputerOutput">RegIndex</span> and <span class="doxyComputerOutput">Channel</span>. <a href="#a0bd21a3c7db6ec5b26c776c6b5fe4b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a65fc2e57549e3d7a37ad516d6523f0">getIndirectAddrRegClass</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2666dab43798128db9f7c436090e2d64">getIndirectIndexBegin</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6963ee4846a440960af3393b33d4e8b0">getIndirectIndexEnd</a> (const MachineFunction &amp;MF) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d622b0faab0d2ae06922e2e5747b2f">buildIndirectWrite</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, unsigned ValueReg, unsigned Address, unsigned OffsetReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build instruction(s) for an indirect register write. <a href="#a63d622b0faab0d2ae06922e2e5747b2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a25e05dcbec8a3858a648945334b51">buildIndirectRead</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, unsigned ValueReg, unsigned Address, unsigned OffsetReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Build instruction(s) for an indirect register read. <a href="#ab0a25e05dcbec8a3858a648945334b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a426079288663f8c9a5cad471d1f08f7c">getMaxAlusPerClause</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030150151483c64bff02ae4f89a50c96">buildDefaultInstruction</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator I, unsigned Opcode, unsigned DstReg, unsigned Src0Reg, unsigned Src1Reg=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>buildDefaultInstruction - This function returns a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with all the instruction modifiers initialized to their default values. <a href="#a030150151483c64bff02ae4f89a50c96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2b6568c134ce283d74d23db8d6b665">buildSlotOfVectorInstruction</a> (MachineBasicBlock &amp;MBB, MachineInstr *MI, unsigned Slot, unsigned DstReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b92da744ddde099abc9476ceca6a26a">buildMovImm</a> (MachineBasicBlock &amp;BB, MachineBasicBlock::iterator I, unsigned DstReg, uint64_t Imm) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa59b61d712578092c3cb3cc7f960498">buildMovInstr</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, unsigned DstReg, unsigned SrcReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a> (const MachineInstr &amp;MI, unsigned Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the index of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> in the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>. <a href="#addaf6e56f2c83eb6d2300026c5430c6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5d76d41819d66002d2e29ffdd5aabe">getOperandIdx</a> (unsigned Opcode, unsigned Op) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the index of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> for the given Opcode. <a href="#acb5d76d41819d66002d2e29ffdd5aabe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66f57da18755676bae1d0f1d47b7da1">setImmOperand</a> (MachineInstr &amp;MI, unsigned Op, int64_t Imm) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function for setting instruction flag values. <a href="#af66f57da18755676bae1d0f1d47b7da1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54891e94b588b8ba0ba2586547e17e31">addFlag</a> (MachineInstr &amp;MI, unsigned Operand, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add one of the MO_FLAG* flags to the specified <span class="doxyComputerOutput">Operand</span>. <a href="#a54891e94b588b8ba0ba2586547e17e31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55db1c9534c0011ebc83c1c5776bed98">isFlagSet</a> (const MachineInstr &amp;MI, unsigned Operand, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the specified <span class="doxyComputerOutput">Flag</span> is set on this <span class="doxyComputerOutput">Operand</span>. <a href="#a55db1c9534c0011ebc83c1c5776bed98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6350749fb33b3fb889a5cb8b5d4ba4">getFlagOp</a> (MachineInstr &amp;MI, unsigned SrcIdx=0, unsigned Flag=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8b734da10672ff4ffc3ec7bf04ec1d">clearFlag</a> (MachineInstr &amp;MI, unsigned Operand, unsigned Flag) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clear the specified flag on the instruction. <a href="#afb8b734da10672ff4ffc3ec7bf04ec1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8666942835ab1d1420a6cf1d83ff5262">isRegisterStore</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203427996c21180b34137c06cad60897">isRegisterLoad</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; int, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bec87347c06d9f3e8a551a16b96233a">ExtractSrcs</a> (MachineInstr &amp;MI, const DenseMap&lt; unsigned, unsigned &gt; &amp;PV, unsigned &amp;ConstCount) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad201e564c0b6a00567e10fbd6ee71819">buildIndirectRead</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, unsigned ValueReg, unsigned Address, unsigned OffsetReg, unsigned AddrChan) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7a691ed79de08465e31257c88b07fc5">buildIndirectWrite</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I, unsigned ValueReg, unsigned Address, unsigned OffsetReg, unsigned AddrChan) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo">R600RegisterInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7eb637e9a290de47b0f949b8d60c6d">RI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39ac4b41100b2422362eebfecb0e3917">ST</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BankSwizzle {#a684a33b88b11aeed1300272bb4cf9f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::R600InstrInfo::BankSwizzle </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALU_VEC_012_SCL_210<a id="a684a33b88b11aeed1300272bb4cf9f73a0832a5c3ff57aae92a383a07ee10062e"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALU_VEC_021_SCL_122<a id="a684a33b88b11aeed1300272bb4cf9f73a119ae5f9f75c4e7e3c3dfb1d27b8ef4c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALU_VEC_120_SCL_212<a id="a684a33b88b11aeed1300272bb4cf9f73a899a4c04ab90aedc9371144fda3ae335"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALU_VEC_102_SCL_221<a id="a684a33b88b11aeed1300272bb4cf9f73a6f0dc124051d7de7745100cc80e1db35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALU_VEC_201<a id="a684a33b88b11aeed1300272bb4cf9f73aa6bf14686367ef224ca73de39bf15703"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALU_VEC_210<a id="a684a33b88b11aeed1300272bb4cf9f73a86885db28ad1792f1b4cd022b368d669"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### R600InstrInfo() {#a1f6b4a34f38efcec5ce770e58c69220f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">R600InstrInfo::R600InstrInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/r600subtarget">R600Subtarget</a> &amp; ST)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFlag() {#a54891e94b588b8ba0ba2586547e17e31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600InstrInfo::addFlag (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Operand, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add one of the MO_FLAG* flags to the specified <span class="doxyComputerOutput">Operand</span>.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#afb8b734da10672ff4ffc3ec7bf04ec1d">clearFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#abe6350749fb33b3fb889a5cb8b5d4ba4">getFlagOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a1ad904deac6dbd960c5c7a473503deb7">HAS_NATIVE_OPERANDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#ae9fe4327414b6fe4c70d220f7b3a698c">MO_FLAG_LAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#ae930f7daa3ebaac65c1bdcb69492ea7c">MO_FLAG_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a9cdbc1e11dd9a91f7f8798472db60fc8">MO_FLAG_NOT_LAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a1403ae81116662ff98bb8441bf5b5772">NUM_MO_FLAGS</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>.</p>


<p>Referenced by <a href="#a648e69f41d62376b996b0b5209022fbd">insertBranch</a>.</p>

</div>
</div>

### analyzeBranch() {#a086f43049b2d52208b7727be22f5e604}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::analyzeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *&amp; FBB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, bool AllowModify)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a54d7439b3555f2971b6fe775ae65fc13">isBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#af47aa3a4bd7d95e1a17e3bc8d20d92e3">isJump</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#abdfa90a858cec4adf79af2ca2985b520">isPredicateSetter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### buildDefaultInstruction() {#a030150151483c64bff02ae4f89a50c96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder R600InstrInfo::buildDefaultInstruction (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned Opcode, unsigned DstReg, unsigned Src0Reg, unsigned Src1Reg=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>buildDefaultInstruction - This function returns a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with all the instruction modifiers initialized to their default values.</p>


<p>You can use this function to avoid manually specifying each instruction modifier operand when building a new instruction.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> with all the instruction modifiers initialized to their default values.</p></dd>
</dl>


<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#a3b92da744ddde099abc9476ceca6a26a">buildMovImm</a>, <a href="#afa59b61d712578092c3cb3cc7f960498">buildMovInstr</a>, <a href="#aca2b6568c134ce283d74d23db8d6b665">buildSlotOfVectorInstruction</a> and <a href="#ae780082016f8641ba5a18009b135d01e">copyPhysReg</a>.</p>

</div>
</div>

### buildIndirectRead() {#ab0a25e05dcbec8a3858a648945334b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder R600InstrInfo::buildIndirectRead (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned ValueReg, unsigned Address, unsigned OffsetReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build instruction(s) for an indirect register read.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The instruction that performs the indirect register read</p></dd>
</dl>


<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### buildIndirectWrite() {#a63d622b0faab0d2ae06922e2e5747b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder R600InstrInfo::buildIndirectWrite (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned ValueReg, unsigned Address, unsigned OffsetReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Build instruction(s) for an indirect register write.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The instruction that performs the indirect register write</p></dd>
</dl>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### buildMovImm() {#a3b92da744ddde099abc9476ceca6a26a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600InstrInfo::buildMovImm (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned DstReg, uint64_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a030150151483c64bff02ae4f89a50c96">buildDefaultInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#af66f57da18755676bae1d0f1d47b7da1">setImmOperand</a>.</p>

</div>
</div>

### buildMovInstr() {#afa59b61d712578092c3cb3cc7f960498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600InstrInfo::buildMovInstr (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned DstReg, unsigned SrcReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a030150151483c64bff02ae4f89a50c96">buildDefaultInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="#ab4c95ecc60411327fd2f6c5d0664224c">expandPostRAPseudo</a>.</p>

</div>
</div>

### buildSlotOfVectorInstruction() {#aca2b6568c134ce283d74d23db8d6b665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * R600InstrInfo::buildSlotOfVectorInstruction (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned Slot, unsigned DstReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1279 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a030150151483c64bff02ae4f89a50c96">buildDefaultInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#af4276d8c21b0e693ccacb27ba6122e70">getSlotedOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a596455aad4b8b4c3aa649e5b227c2ee8">llvm::AMDGPUSubtarget::R700</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>, <a href="#af66f57da18755676bae1d0f1d47b7da1">setImmOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>

</div>
</div>

### calculateIndirectAddress() {#a0bd21a3c7db6ec5b26c776c6b5fe4b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600InstrInfo::calculateIndirectAddress (unsigned RegIndex, unsigned Channel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the "Indirect Address" for the given <span class="doxyComputerOutput">RegIndex</span> and <span class="doxyComputerOutput">Channel</span>.</p>


<p>We model indirect addressing using a virtual address space that can be accessed with loads and stores. The "Indirect Address" is the memory address in this virtual address space that maps to the given <span class="doxyComputerOutput">RegIndex</span> and <span class="doxyComputerOutput">Channel</span>.</p>


<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#ab4c95ecc60411327fd2f6c5d0664224c">expandPostRAPseudo</a>.</p>

</div>
</div>

### canBeConsideredALU() {#a507703ee09a583ff911a8d09cd409b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::canBeConsideredALU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <span class="doxyComputerOutput">Opcode</span> represents an ALU instruction or an instruction that will be lowered in ExpandSpecialInstrs <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a>.</p></dd>
</dl>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#ad80e1e5645d57c506cb63732f576ce81">isALUInstr</a>, <a href="#a891797e1ad8f29e9ed5d3443f10dc82e">isCubeOp</a>, <a href="#a5bad3393698345347bc9ef02419fd8cd">isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### clearFlag() {#afb8b734da10672ff4ffc3ec7bf04ec1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600InstrInfo::clearFlag (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Operand, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clear the specified flag on the instruction.</p>

<p>Declaration at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#abe6350749fb33b3fb889a5cb8b5d4ba4">getFlagOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a1ad904deac6dbd960c5c7a473503deb7">HAS_NATIVE_OPERANDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a1403ae81116662ff98bb8441bf5b5772">NUM_MO_FLAGS</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a>.</p>


<p>Referenced by <a href="#a54891e94b588b8ba0ba2586547e17e31">addFlag</a> and <a href="#a5c764241e49b1b62cbe5153f384ef196">removeBranch</a>.</p>

</div>
</div>

### ClobbersPredicate() {#ad70329ea652d85d2cdc7095f7ad9c453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::ClobbersPredicate (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Pred, bool SkipDead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 928 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#abdfa90a858cec4adf79af2ca2985b520">isPredicateSetter</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### copyPhysReg() {#ae780082016f8641ba5a18009b135d01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600InstrInfo::copyPhysReg (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DestReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SrcReg, bool KillSrc, bool RenamableDest=false, bool RenamableSrc=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="#a030150151483c64bff02ae4f89a50c96">buildDefaultInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo/#a9769d7d0cd244192d98524db21e2f3c2">llvm::R600RegisterInfo::getSubRegFromChannel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a8a82683fccdef8a5ef772ef03277aee7">llvm::MachineOperand::setIsKill</a>.</p>

</div>
</div>

### CreateTargetScheduleState() {#a74e6aef88dec63b3e87ab2a3fc6f9c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DFAPacketizer * R600InstrInfo::CreateTargetScheduleState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ae1f9b65239ddc3a0662b679817e477d3">llvm::TargetSubtargetInfo::getInstrItineraryData</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### definesAddressRegister() {#a3f981149d5958196da00178c5640d576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::definesAddressRegister (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### expandPostRAPseudo() {#ab4c95ecc60411327fd2f6c5d0664224c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::expandPostRAPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 986 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#afa59b61d712578092c3cb3cc7f960498">buildMovInstr</a>, <a href="#a0bd21a3c7db6ec5b26c776c6b5fe4b13">calculateIndirectAddress</a>, <a href="#a3a65fc2e57549e3d7a37ad516d6523f0">getIndirectAddrRegClass</a>, <a href="#a203427996c21180b34137c06cad60897">isRegisterLoad</a>, <a href="#a8666942835ab1d1420a6cf1d83ff5262">isRegisterStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### FindSwizzleForVectorSlot() {#accae71a18e9054f96a7919785976ee15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::FindSwizzleForVectorSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &gt; &amp; IGSrcs, std::vector&lt; <a href="#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> &gt; &amp; SwzCandidate, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &amp; TransSrcs, <a href="#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> TransSwz)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enumerate all possible Swizzle sequence to find one that can meet all read port requirements.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a2fce8516b6f35622360433c3bae2b70c">isLegalUpTo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#add9477a0a18c76d6cf088f26c7af54e3">NextPossibleSolution</a>.</p>


<p>Referenced by <a href="#ad4bc494da88251a58ca644dec0d15a2e">fitsReadPortLimitations</a>.</p>

</div>
</div>

### fitsConstReadLimitations() {#a537788ca2a4d7bbdbfad2ac8e5dfabca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::fitsConstReadLimitations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; MIs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An instruction group can only access 2 channel pair (either [XY] or [ZW]) from KCache bank on R700+.</p>


<p>This function check if MI set in input meet this limitations</p>


<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a537788ca2a4d7bbdbfad2ac8e5dfabca">fitsConstReadLimitations</a>, <a href="#ae6f1cb7931164d888acd081fa41e6246">getSrcs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="#ad80e1e5645d57c506cb63732f576ce81">isALUInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afd7c135e18f2d7253d4f8545cd7b1756">llvm::SmallSet&lt; T, N, C &gt;::size</a>.</p>


<p>Referenced by <a href="#a537788ca2a4d7bbdbfad2ac8e5dfabca">fitsConstReadLimitations</a>.</p>

</div>
</div>

### fitsConstReadLimitations() {#ad2602638ef43bcf2b073625f2bd0d9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::fitsConstReadLimitations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; unsigned &gt; &amp; Consts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Same but using const index set instead of MI set.</p>

<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### fitsReadPortLimitations() {#ad4bc494da88251a58ca644dec0d15a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::fitsReadPortLimitations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; MIs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; PV, std::vector&lt; <a href="#a684a33b88b11aeed1300272bb4cf9f73">BankSwizzle</a> &gt; &amp; BS, bool isLastAluTrans)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given the order VEC_012 &lt; VEC_021 &lt; VEC_120 &lt; VEC_102 &lt; VEC_201 &lt; VEC_210 returns true and the first (in lexical order) <a href="#a684a33b88b11aeed1300272bb4cf9f73">BankSwizzle</a> affectation starting from the one already provided in the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Group MIs that fits Read Port limitations in BS if available.</p>


<p>Otherwise returns false and undefined content in BS. isLastAluTrans should be set if the last Alu of MIs will be executed on Trans ALU. In this case, ValidTSwizzle returns the <a href="#a684a33b88b11aeed1300272bb4cf9f73">BankSwizzle</a> value to apply to the last instruction. PV holds GPR to PV registers in the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Group MIs.</p>


<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a684a33b88b11aeed1300272bb4cf9f73a0832a5c3ff57aae92a383a07ee10062e">ALU_VEC_012_SCL_210</a>, <a href="#a684a33b88b11aeed1300272bb4cf9f73a119ae5f9f75c4e7e3c3dfb1d27b8ef4c">ALU_VEC_021_SCL_122</a>, <a href="#a684a33b88b11aeed1300272bb4cf9f73a6f0dc124051d7de7745100cc80e1db35">ALU_VEC_102_SCL_221</a>, <a href="#a684a33b88b11aeed1300272bb4cf9f73a899a4c04ab90aedc9371144fda3ae335">ALU_VEC_120_SCL_212</a>, <a href="#accae71a18e9054f96a7919785976ee15">FindSwizzleForVectorSlot</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#ab4f8cbf733d43f4c7fb0d2f2699813e5">isConstCompatible</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getFlagOp() {#abe6350749fb33b3fb889a5cb8b5d4ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineOperand &amp; R600InstrInfo::getFlagOp (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned SrcIdx=0, unsigned Flag=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcIdx</td>
<td class="doxyParamItemDescription"><p>The register source to set the flag on (e.g src0, src1, src2)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Flag</td>
<td class="doxyParamItemDescription"><p>The flag being set.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the operand containing the flags for this instruction.</p></dd>
</dl>


<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#af0879284b65ffa68ff468f299b465a39">GET_FLAG_OPERAND_IDX</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a1ad904deac6dbd960c5c7a473503deb7">HAS_NATIVE_OPERANDS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#adc4fb86109ffdf8ce21d7b2d36c9352e">MO_FLAG_ABS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a190837f9d51526f9c7df31ee77c7acf3">MO_FLAG_CLAMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#ae9fe4327414b6fe4c70d220f7b3a698c">MO_FLAG_LAST</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#ae930f7daa3ebaac65c1bdcb69492ea7c">MO_FLAG_MASK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a73ea1e4ec493abfd161da3e3338d54a1">MO_FLAG_NEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a9cdbc1e11dd9a91f7f8798472db60fc8">MO_FLAG_NOT_LAST</a> and <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da65fb6d999803c0872b80b25f3c77a893">R600_InstFlag::OP3</a>.</p>


<p>Referenced by <a href="#a54891e94b588b8ba0ba2586547e17e31">addFlag</a> and <a href="#afb8b734da10672ff4ffc3ec7bf04ec1d">clearFlag</a>.</p>

</div>
</div>

### getIndirectAddrRegClass() {#a3a65fc2e57549e3d7a37ad516d6523f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass * R600InstrInfo::getIndirectAddrRegClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The register class to be used for loading and storing values from an "Indirect Address" .</p></dd>
</dl>


<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#ab4c95ecc60411327fd2f6c5d0664224c">expandPostRAPseudo</a> and <a href="#a2666dab43798128db9f7c436090e2d64">getIndirectIndexBegin</a>.</p>

</div>
</div>

### getIndirectIndexBegin() {#a2666dab43798128db9f7c436090e2d64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600InstrInfo::getIndirectIndexBegin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the smallest register index that will be accessed by an indirect read or write or -1 if indirect addressing is not used by this program.</p></dd>
</dl>


<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a60b6974966381f08079722f2258a0039">llvm::TargetRegisterClass::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#a3a65fc2e57549e3d7a37ad516d6523f0">getIndirectAddrRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab4b44bc5aa744df4f8b70f971e8dcbf1">llvm::MachineFrameInfo::getNumObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a140a96e49ab5e53e99c3233291d98eb4">llvm::TargetRegisterClass::getNumRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#ad4cd0fd35859157ba99c4206679d3824">llvm::TargetRegisterClass::getRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a6963ee4846a440960af3393b33d4e8b0">getIndirectIndexEnd</a> and <a href="#aa21fe05557eb564cf547a20ccf43d9f5">reserveIndirectRegisters</a>.</p>

</div>
</div>

### getIndirectIndexEnd() {#a6963ee4846a440960af3393b33d4e8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600InstrInfo::getIndirectIndexEnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the largest register index that will be accessed by an indirect read or write or -1 if indirect addressing is not used by this program.</p></dd>
</dl>


<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="#a2666dab43798128db9f7c436090e2d64">getIndirectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ab4b44bc5aa744df4f8b70f971e8dcbf1">llvm::MachineFrameInfo::getNumObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a0509430713d587eba74220a8375948a8">llvm::MachineFrameInfo::hasVarSizedObjects</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#aa21fe05557eb564cf547a20ccf43d9f5">reserveIndirectRegisters</a>.</p>

</div>
</div>

### getInstrLatency() {#a3317ad36612bd0a93dad2af012182dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int R600InstrInfo::getInstrLatency (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instritinerarydata">InstrItineraryData</a> * ItinData, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned * PredCost=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### getMaxAlusPerClause() {#a426079288663f8c9a5cad471d1f08f7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600InstrInfo::getMaxAlusPerClause ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### getOperandIdx() {#addaf6e56f2c83eb6d2300026c5430c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600InstrInfo::getOperandIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the index of <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> in the <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>-1 if the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> does not contain the specified <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p></dd>
</dl>


<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aca2b6568c134ce283d74d23db8d6b665">buildSlotOfVectorInstruction</a>, <a href="#ae780082016f8641ba5a18009b135d01e">copyPhysReg</a>, <a href="#ad4bc494da88251a58ca644dec0d15a2e">fitsReadPortLimitations</a>, <a href="#abe6350749fb33b3fb889a5cb8b5d4ba4">getFlagOp</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="#ab858beae728e107227a9e07759588087">getSelIdx</a>, <a href="#ae6f1cb7931164d888acd081fa41e6246">getSrcs</a>, <a href="#ab64e90b1e671bf82b2dbcc831d63ddbf">isLDSRetInstr</a>, <a href="#a4501178e61d2f154d7b9bc4fc519fe68">PredicateInstruction</a> and <a href="#af66f57da18755676bae1d0f1d47b7da1">setImmOperand</a>.</p>

</div>
</div>

### getOperandIdx() {#acb5d76d41819d66002d2e29ffdd5aabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600InstrInfo::getOperandIdx (unsigned Opcode, unsigned Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the index of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> for the given Opcode.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>-1 if the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> does not contain the specified <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span>.</p></dd>
</dl>


<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1347 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### getPredicationCost() {#ac39a8558f3e2c9d7806eab38a2bc3fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned int R600InstrInfo::getPredicationCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### getRegisterInfo() {#a161e7f13bb4970a80ac16e93a7ebee73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600RegisterInfo &amp; llvm::R600InstrInfo::getRegisterInfo ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>

</div>
</div>

### getSelIdx() {#ab858beae728e107227a9e07759588087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int R600InstrInfo::getSelIdx (unsigned Opcode, unsigned SrcIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The operand Index for the Sel operand given an index to one of the instruction's src operands.</p></dd>
</dl>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>.</p>

</div>
</div>

### getSrcs() {#ae6f1cb7931164d888acd081fa41e6246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; std::pair&lt; MachineOperand *, int64_t &gt;, 3 &gt; R600InstrInfo::getSrcs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a pair for each src of an ALU instructions. The first member of a pair is the register id. If register is ALU_CONST, second member is SEL. If register is ALU_LITERAL, second member is IMM. Otherwise, second member value is undefined.</p></dd>
</dl>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ab0d1155c8c38e84cbe387998fd2e517e">llvm::MachineOperand::isGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a537788ca2a4d7bbdbfad2ac8e5dfabca">fitsConstReadLimitations</a>.</p>

</div>
</div>

### hasInstrModifiers() {#a1215beb8e209f4246f9809770be405d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::hasInstrModifiers (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da5c7761a47418fadaea243842b44f7c7d">R600_InstFlag::OP1</a>, <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da282bbf9f0d832c637c954069fd93a16d">R600_InstFlag::OP2</a> and <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da65fb6d999803c0872b80b25f3c77a893">R600_InstFlag::OP3</a>.</p>

</div>
</div>

### insertBranch() {#a648e69f41d62376b996b0b5209022fbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600InstrInfo::insertBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * FBB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL, int * BytesAdded=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a54891e94b588b8ba0ba2586547e17e31">addFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a0aaab3b6598c7349f766220c8b318744">findFirstPredicateSetterFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a869d77ae27dd6a3e2883d5988c66dd70">FindLastAluClause</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#afeec7edbcb979a86b4d931ecce39750c">MO_FLAG_PUSH</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a1441f79530bc7f3a89118bb8067eac69">TBB</a>.</p>

</div>
</div>

### isALUInstr() {#ad80e1e5645d57c506cb63732f576ce81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isALUInstr (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if this <span class="doxyComputerOutput">Opcode</span> represents an ALU instruction.</p></dd>
</dl>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da756c9e9957dd5d8182f18147ae32a1ee">R600_InstFlag::ALU_INST</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>


<p>Referenced by <a href="#a507703ee09a583ff911a8d09cd409b68">canBeConsideredALU</a>, <a href="#a537788ca2a4d7bbdbfad2ac8e5dfabca">fitsConstReadLimitations</a> and <a href="#acbfbaa0e925b1f975b016053d752e899">readsLDSSrcReg</a>.</p>

</div>
</div>

### isCubeOp() {#a891797e1ad8f29e9ed5d3443f10dc82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isCubeOp (unsigned opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a507703ee09a583ff911a8d09cd409b68">canBeConsideredALU</a>.</p>

</div>
</div>

### isExport() {#add24e1463a36a613e008ed84227b4785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isExport (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da3c896030b8fb10a4fefaffd08e5c5918">R600_InstFlag::IS_EXPORT</a>.</p>

</div>
</div>

### isFlagSet() {#a55db1c9534c0011ebc83c1c5776bed98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::R600InstrInfo::isFlagSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Operand, unsigned Flag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the specified <span class="doxyComputerOutput">Flag</span> is set on this <span class="doxyComputerOutput">Operand</span>.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isLDSInstr() {#a89de148c8666da38bdf2b414f9e254ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isLDSInstr (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da235b9c63d7ec658a5b8b478667388870">R600_InstFlag::LDS_1A</a>, <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940daa34c84dd5b6e2f1591e971fbe5f08467">R600_InstFlag::LDS_1A1D</a> and <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940dab4b8bb828479e92fedd7719ef824ded9">R600_InstFlag::LDS_1A2D</a>.</p>


<p>Referenced by <a href="#ab64e90b1e671bf82b2dbcc831d63ddbf">isLDSRetInstr</a>.</p>

</div>
</div>

### isLDSRetInstr() {#ab64e90b1e671bf82b2dbcc831d63ddbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isLDSRetInstr (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a> and <a href="#a89de148c8666da38bdf2b414f9e254ec">isLDSInstr</a>.</p>

</div>
</div>

### isLegalToSplitMBBAt() {#a50503e8c79cfae86f42c25b30c4dee2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isLegalToSplitMBBAt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if <span class="doxyComputerOutput">MBBI</span> can be moved into a new basic.</p></dd>
</dl>


<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>.</p>

</div>
</div>

### isLegalUpTo() {#a2fce8516b6f35622360433c3bae2b70c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600InstrInfo::isLegalUpTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &gt; &amp; IGSrcs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> &gt; &amp; Swz, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; &amp; TransSrcs, <a href="#a684a33b88b11aeed1300272bb4cf9f73">R600InstrInfo::BankSwizzle</a> TransSwz)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns how many MIs (whose inputs are represented by IGSrcs) can be packed in the same <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> Group while meeting read port limitations given a Swz swizzle sequence.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a684a33b88b11aeed1300272bb4cf9f73a0832a5c3ff57aae92a383a07ee10062e">ALU_VEC_012_SCL_210</a>, <a href="#a684a33b88b11aeed1300272bb4cf9f73a119ae5f9f75c4e7e3c3dfb1d27b8ef4c">ALU_VEC_021_SCL_122</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a02bc7e1abaae72119abf9ee69086c5fa">GET_REG_INDEX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#aa58438639da1cbfa02c522d1a0132de7">getTransSwizzle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a97379d7fa3126a13ded0f0d0da0b451d">Swizzle</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="#accae71a18e9054f96a7919785976ee15">FindSwizzleForVectorSlot</a>.</p>

</div>
</div>

### isMov() {#a1fddf85baa47d23103126f2a45ea3a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isMov (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### isPredicable() {#ab334b6a433595c3b14311e50ed433119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isPredicable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 840 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#adf401885b0d39da5774814718bc889c8">llvm::TargetInstrInfo::isPredicable</a>, <a href="#a5bad3393698345347bc9ef02419fd8cd">isVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isPredicated() {#ab39a8eb989f01d8ed539a6fe6a210ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isPredicated (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isProfitableToDupForIfCvt() {#a2700054a144dc843858ac4954f53e2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isProfitableToDupForIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned NumCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 881 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isProfitableToIfCvt() {#aa83513847e40eb20946e50e05d50fc3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isProfitableToIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, unsigned NumCycles, unsigned ExtraPredCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>

</div>
</div>

### isProfitableToIfCvt() {#a49fa0640f041ac13c4f7d6eacf03278b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isProfitableToIfCvt (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TMBB, unsigned NumTCycles, unsigned ExtraTCycles, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FMBB, unsigned NumFCycles, unsigned ExtraFCycles, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Probability)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### isProfitableToUnpredicate() {#a508277c4ff138f71ec87b10f00063586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isProfitableToUnpredicate (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TMBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### isReductionOp() {#a7f44398d0ba1f70349d99b68940febde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isReductionOp (unsigned opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### isRegisterLoad() {#a203427996c21180b34137c06cad60897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::R600InstrInfo::isRegisterLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/r600instrflags/#ae901caee918a3e2914d42471a597869ea3b26f46bad7c43d4dd56e55b5089033c">llvm::R600InstrFlags::REGISTER_LOAD</a>.</p>


<p>Referenced by <a href="#ab4c95ecc60411327fd2f6c5d0664224c">expandPostRAPseudo</a>.</p>

</div>
</div>

### isRegisterStore() {#a8666942835ab1d1420a6cf1d83ff5262}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::R600InstrInfo::isRegisterStore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/r600instrflags/#ae901caee918a3e2914d42471a597869ea17ad87595503db232246a276d4a03ca7">llvm::R600InstrFlags::REGISTER_STORE</a>.</p>


<p>Referenced by <a href="#ab4c95ecc60411327fd2f6c5d0664224c">expandPostRAPseudo</a>.</p>

</div>
</div>

### isTransOnly() {#a6b3de1aca767b960a302308f3c463317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isTransOnly (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>


<p>Referenced by <a href="#ae4040056c150bccdd7d14849ffa9486d">isTransOnly</a>.</p>

</div>
</div>

### isTransOnly() {#ae4040056c150bccdd7d14849ffa9486d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isTransOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a6b3de1aca767b960a302308f3c463317">isTransOnly</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### isVector() {#a5bad3393698345347bc9ef02419fd8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isVector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Vector instructions are instructions that must fill all instruction slots within an instruction group.</p>

<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/r600-instflag/#a23106439cc906be24dc8953eedd3940da9fcf11654df8fda1a017ac888e522f8c">R600_InstFlag::VECTOR</a>.</p>


<p>Referenced by <a href="#a507703ee09a583ff911a8d09cd409b68">canBeConsideredALU</a> and <a href="#ab334b6a433595c3b14311e50ed433119">isPredicable</a>.</p>

</div>
</div>

### isVectorOnly() {#adbb5663da5534317c035227ab390bf36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isVectorOnly (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>.</p>


<p>Referenced by <a href="#a0aa7e2ed9eabcb9cc26a590209d53d9d">isVectorOnly</a>.</p>

</div>
</div>

### isVectorOnly() {#a0aa7e2ed9eabcb9cc26a590209d53d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::isVectorOnly (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#adbb5663da5534317c035227ab390bf36">isVectorOnly</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### mustBeLastInClause() {#a6051ea915d00d989d449bb69ab996d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::mustBeLastInClause (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### PredicateInstruction() {#a4501178e61d2f154d7b9bc4fc519fe68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::PredicateInstruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>

</div>
</div>

### readsLDSSrcReg() {#acbfbaa0e925b1f975b016053d752e899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::readsLDSSrcReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#ad80e1e5645d57c506cb63732f576ce81">isALUInstr</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### removeBranch() {#a5c764241e49b1b62cbe5153f384ef196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned R600InstrInfo::removeBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, int * BytesRemoved=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 766 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#afb8b734da10672ff4ffc3ec7bf04ec1d">clearFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a0aaab3b6598c7349f766220c8b318744">findFirstPredicateSetterFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp/#a869d77ae27dd6a3e2883d5988c66dd70">FindLastAluClause</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#afeec7edbcb979a86b4d931ecce39750c">MO_FLAG_PUSH</a>.</p>

</div>
</div>

### reserveIndirectRegisters() {#aa21fe05557eb564cf547a20ccf43d9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600InstrInfo::reserveIndirectRegisters (<a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; Reserved, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/r600registerinfo">R600RegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reserve the registers that may be accessed using indirect addressing.</p>

<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="#a2666dab43798128db9f7c436090e2d64">getIndirectIndexBegin</a>, <a href="#a6963ee4846a440960af3393b33d4e8b0">getIndirectIndexEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuframelowering/#a3daff493f635e8f30d6c8cb7b967b860">llvm::AMDGPUFrameLowering::getStackWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8c9d5a3046b96979a032c218e858cd15a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### reverseBranchCondition() {#a03c6876ed7ada0d971240509db503dc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::reverseBranchCondition (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 895 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2feaa1c69335c6b9028076cd68c7a5f5">llvm::MachineOperand::setImm</a> and <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>.</p>

</div>
</div>

### setImmOperand() {#af66f57da18755676bae1d0f1d47b7da1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void R600InstrInfo::setImmOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned Op, int64_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function for setting instruction flag values.</p>

<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1351 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#addaf6e56f2c83eb6d2300026c5430c6d">getOperandIdx</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a3b92da744ddde099abc9476ceca6a26a">buildMovImm</a> and <a href="#aca2b6568c134ce283d74d23db8d6b665">buildSlotOfVectorInstruction</a>.</p>

</div>
</div>

### usesAddressRegister() {#a0aa3d48f55eef628d97bb21156177f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::usesAddressRegister (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### usesTextureCache() {#a2a26ade8a5837be3ac8373a6edc81350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::usesTextureCache (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#afa52d19180ca48825c8a2af55ebb3ee0">IS_TEX</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a39081f15fe8b8f49b5476e7a23fb735c">IS_VTX</a>.</p>


<p>Referenced by <a href="#a228e67ed635dc4282489be7f3fc1c2e8">usesTextureCache</a>.</p>

</div>
</div>

### usesTextureCache() {#a228e67ed635dc4282489be7f3fc1c2e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::usesTextureCache (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5688c3d8cf734f824f2637b7bc91e2cb">llvm::AMDGPU::isCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a2a26ade8a5837be3ac8373a6edc81350">usesTextureCache</a> and <a href="#a0220f9eee026db654316584948dede8d">usesVertexCache</a>.</p>

</div>
</div>

### usesVertexCache() {#a0220f9eee026db654316584948dede8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::usesVertexCache (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600defines-h/#a39081f15fe8b8f49b5476e7a23fb735c">IS_VTX</a>.</p>


<p>Referenced by <a href="#a228e67ed635dc4282489be7f3fc1c2e8">usesTextureCache</a> and <a href="#abbae172c51615eb52ec12f0af642de64">usesVertexCache</a>.</p>

</div>
</div>

### usesVertexCache() {#abbae172c51615eb52ec12f0af642de64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool R600InstrInfo::usesVertexCache (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a5f494edc0a569c7fc9ff4181243be1ed">llvm::Function::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5688c3d8cf734f824f2637b7bc91e2cb">llvm::AMDGPU::isCompute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a0220f9eee026db654316584948dede8d">usesVertexCache</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildIndirectRead() {#ad201e564c0b6a00567e10fbd6ee71819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder R600InstrInfo::buildIndirectRead (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned ValueReg, unsigned Address, unsigned OffsetReg, unsigned AddrChan)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### buildIndirectWrite() {#ac7a691ed79de08465e31257c88b07fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder R600InstrInfo::buildIndirectWrite (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I, unsigned ValueReg, unsigned Address, unsigned OffsetReg, unsigned AddrChan)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 1083 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

### ExtractSrcs() {#a4bec87347c06d9f3e8a551a16b96233a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::pair&lt; int, unsigned &gt; &gt; R600InstrInfo::ExtractSrcs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, unsigned &gt; &amp; PV, unsigned &amp; ConstCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### RI {#abb7eb637e9a290de47b0f949b8d60c6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600RegisterInfo llvm::R600InstrInfo::RI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>

</div>
</div>

### ST {#a39ac4b41100b2422362eebfecb0e3917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const R600Subtarget&amp; llvm::R600InstrInfo::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-cpp">R600InstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600instrinfo-h">R600InstrInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
