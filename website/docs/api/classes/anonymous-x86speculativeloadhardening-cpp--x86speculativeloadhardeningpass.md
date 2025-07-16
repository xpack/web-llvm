---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86SpeculativeLoadHardeningPass` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a626d52a8457ef92d87b702df1cb7f">X86SpeculativeLoadHardeningPass</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc095bc1100ba5f1e44a49e741303f28">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#afc095bc1100ba5f1e44a49e741303f28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862b3b4b5ed250fcfb2d6f9a130f4a0c">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#a862b3b4b5ed250fcfb2d6f9a130f4a0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a395357d9b35c4d32866dac3ab09a335a">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this. <a href="#a395357d9b35c4d32866dac3ab09a335a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac91f80e5fe7079cb556e107af58aa915">hardenEdgesWithLFENCE</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements the naive hardening approach of putting an LFENCE after every potentially mis-predicted control flow construct. <a href="#ac91f80e5fe7079cb556e107af58aa915">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; BlockCondInfo, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9288e68efcb80c36f717b85f956b8c22">collectBlockCondInfo</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a561226da60bb592263645c4c2221e2b3">tracePredStateThroughCFG</a> (MachineFunction &amp;MF, ArrayRef&lt; BlockCondInfo &gt; Infos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through the CFG, instrumenting each conditional branch such that misspeculation through an edge will poison the predicate state. <a href="#a561226da60bb592263645c4c2221e2b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1705e42db56a885ff72109bae739a5">unfoldCallAndJumpLoads</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e2041e476780454dd8421e1ba23bca">tracePredStateThroughIndirectBranches</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through indirect branches, instrumenting them to poison the state if a target is reached that does not match the expected target. <a href="#a99e2041e476780454dd8421e1ba23bca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83e6c452f7fdc25aeff4b8d56ffa68f2">tracePredStateThroughBlocksAndHarden</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through each of the blocks in the function, hardening everything necessary along the way. <a href="#a83e6c452f7fdc25aeff4b8d56ffa68f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51c88fadd2d858ca48009266fa4f9e20">saveEFLAGS</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertPt, const DebugLoc &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save EFLAGS into the returned GPR. <a href="#a51c88fadd2d858ca48009266fa4f9e20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fe992bc7311068a5e174e5115345e5">restoreEFLAGS</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertPt, const DebugLoc &amp;Loc, Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore EFLAGS from the provided GPR. <a href="#a57fe992bc7311068a5e174e5115345e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf98c3ecbac31ed744d67bd7e1fd6ba">mergePredStateIntoSP</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertPt, const DebugLoc &amp;Loc, unsigned PredStateReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Takes the current predicate state (in a register) and merges it into the stack pointer. <a href="#a6bf98c3ecbac31ed744d67bd7e1fd6ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a124c30984d35bb558c28bed24433e677">extractPredStateFromSP</a> (MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertPt, const DebugLoc &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extracts the predicate state stored in the high bits of the stack pointer. <a href="#a124c30984d35bb558c28bed24433e677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc96bcaec5dcc9c812aa674278bf8b0">hardenLoadAddr</a> (MachineInstr &amp;MI, MachineOperand &amp;BaseMO, MachineOperand &amp;IndexMO, SmallDenseMap&lt; unsigned, unsigned, 32 &gt; &amp;AddrRegToHardenedReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2590a4dd70cb8fc910e778999a149d">sinkPostLoadHardenedInst</a> (MachineInstr &amp;MI, SmallPtrSetImpl&lt; MachineInstr * &gt; &amp;HardenedInstrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb1b7b0795af4afaad6fbe2bbad1b4f">canHardenRegister</a> (Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6192a88ae0ffb9aae6d2777f03bc2051">hardenValueInRegister</a> (Register Reg, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator InsertPt, const DebugLoc &amp;Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Harden a value in a register. <a href="#a6192a88ae0ffb9aae6d2777f03bc2051">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a63f76260d0e7c60d0acca5da94973c">hardenPostLoad</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Harden a load by hardening the loaded value in the defined register. <a href="#a9a63f76260d0e7c60d0acca5da94973c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79aa2da36f644b0a5894e49159921fe7">hardenReturnInstr</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Harden a return instruction. <a href="#a79aa2da36f644b0a5894e49159921fe7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3bcfd049a584052d380b5b9f6d5910">tracePredStateThroughCall</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through a call. <a href="#a9e3bcfd049a584052d380b5b9f6d5910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27e361ee6ed1a69fa63aa5ce5a93cac9">hardenIndirectCallOrJumpInstr</a> (MachineInstr &amp;MI, SmallDenseMap&lt; unsigned, unsigned, 32 &gt; &amp;AddrRegToHardenedReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An attacker may speculatively store over a value that is then speculatively loaded and used as the target of an indirect call or jump instruction. <a href="#a27e361ee6ed1a69fa63aa5ce5a93cac9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d274b65a12e504061a83af5e701001">Subtarget</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455d25db0312916c89c3b89268a74736">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo">X86InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab25b96ceead471840bc2c0bf4ea9d504">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d888e74c1090f8752b50cbaa7e9e6b8">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; PredState &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90994b9a84a001b8c9e5ee90630e184">PS</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a845bb9b2068e7fd8052fc0e53ed461e5">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pass identification, replacement for typeid. <a href="#a845bb9b2068e7fd8052fc0e53ed461e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86SpeculativeLoadHardeningPass() {#a77a626d52a8457ef92d87b702df1cb7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::X86SpeculativeLoadHardeningPass ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>


<p>References <a href="#a845bb9b2068e7fd8052fc0e53ed461e5">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a65f5a5f0179a8e1cbb425fe8bf33069d">llvm::createX86SpeculativeLoadHardeningPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a395357d9b35c4d32866dac3ab09a335a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp; AU)</td>
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

<p>getAnalysisUsage - Subclasses that override getAnalysisUsage must call this.</p>


<p>For MachineFunctionPasses, calling AU.preservesCFG() indicates that the pass does not modify the MachineBasicBlock CFG.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getPassName() {#afc095bc1100ba5f1e44a49e741303f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>


<p>Referenced by <a href="#a862b3b4b5ed250fcfb2d6f9a130f4a0c">runOnMachineFunction</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a862b3b4b5ed250fcfb2d6f9a130f4a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86SpeculativeLoadHardeningPass::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab0789854909cf47f640a85fa2bac29c7">llvm::MachineFunction::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a22244f1af2bc880ef42bfd77068ce13a">canonicalizePHIOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d931af4280c80a837ee409eb85104f7">llvm::MachineFunction::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a964a795e07ed117f8049f44b16739763">EnableSpeculativeLoadHardening</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a9d017af749f76484cb9aec9ff6e4330c">llvm::MachineFunction::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a5ee11464d0d2e030d95afb0db83b801d">FenceCallAndRet</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d142c9e7c066059e15232c56dec9e2e">llvm::MachineFunction::getName</a>, <a href="#afc095bc1100ba5f1e44a49e741303f28">getPassName</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a921b17e18b1d37ab8ca2b7375df1addf">HardenEdgesWithLFENCE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#ade91f65a65e423e2002fb9b25b7b2a5c">HardenIndirectCallsAndJumps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a3e42304d79c25684c4d464fd35fb868f">HardenInterprocedurally</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#abe47da1ba1b5239bb67b26d5ebbca491">hasVulnerableLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a61a42c85bd86c6ca4554e27d33c3f798">llvm::MachineOperand::setIsDead</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a8efc9cbc802adc2bb2673b4ba6308869">llvm::MachineFunction::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canHardenRegister() {#a8fb1b7b0795af4afaad6fbe2bbad1b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86SpeculativeLoadHardeningPass::canHardenRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### collectBlockCondInfo() {#a9288e68efcb80c36f717b85f956b8c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; X86SpeculativeLoadHardeningPass::BlockCondInfo, 16 &gt; X86SpeculativeLoadHardeningPass::collectBlockCondInfo (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### extractPredStateFromSP() {#a124c30984d35bb558c28bed24433e677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86SpeculativeLoadHardeningPass::extractPredStateFromSP (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extracts the predicate state stored in the high bits of the stack pointer.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### hardenEdgesWithLFENCE() {#ac91f80e5fe7079cb556e107af58aa915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::hardenEdgesWithLFENCE (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implements the naive hardening approach of putting an LFENCE after every potentially mis-predicted control flow construct.</p>


<p>We include this as an alternative mostly for the purpose of comparison. The performance impact of this is expected to be extremely severe and not practical for any real-world users.</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### hardenIndirectCallOrJumpInstr() {#a27e361ee6ed1a69fa63aa5ce5a93cac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::hardenIndirectCallOrJumpInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, unsigned, 32 &gt; &amp; AddrRegToHardenedReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An attacker may speculatively store over a value that is then speculatively loaded and used as the target of an indirect call or jump instruction.</p>


<p>This is called Spectre v1.2 or Bounds Check Bypass Store (BCBS) and is described in this paper: <a href="https://people.csail.mit.edu/vlk/spectre11.pdf">https://people.csail.mit.edu/vlk/spectre11.pdf</a></p>


<p>When this happens, the speculative execution of the call or jump will end up being steered to this attacker controlled address. While most such loads will be adequately hardened already, we want to ensure that they are definitively treated as needing post-load hardening. While address hardening is sufficient to prevent secret data from leaking to the attacker, it may not be sufficient to prevent an attacker from steering speculative execution. We forcibly unfolded all relevant loads above and so will always have an opportunity to post-load harden here, we just need to scan for cases not already flagged and add them.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### hardenLoadAddr() {#a2cc96bcaec5dcc9c812aa674278bf8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::hardenLoadAddr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; BaseMO, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; IndexMO, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; unsigned, unsigned, 32 &gt; &amp; AddrRegToHardenedReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### hardenPostLoad() {#a9a63f76260d0e7c60d0acca5da94973c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86SpeculativeLoadHardeningPass::hardenPostLoad (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Harden a load by hardening the loaded value in the defined register.</p>


<p>We can harden a non-leaking load into a register without touching the address by just hiding all of the loaded bits during misspeculation. We use an <span class="doxyComputerOutput">or</span> instruction to do this because we set up our poison value as all ones. And the goal is just for the loaded bits to not be exposed to execution and coercing them to one is sufficient.</p>


<p>Returns the newly hardened register.</p>


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### hardenReturnInstr() {#a79aa2da36f644b0a5894e49159921fe7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::hardenReturnInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Harden a return instruction.</p>


<p>Returns implicitly perform a load which we need to harden. Without hardening this load, an attacker my speculatively write over the return address to steer speculation of the return to an attacker controlled address. This is called Spectre v1.1 or Bounds Check Bypass Store (BCBS) and is described in this paper: <a href="https://people.csail.mit.edu/vlk/spectre11.pdf">https://people.csail.mit.edu/vlk/spectre11.pdf</a></p>


<p>We can harden this by introducing an LFENCE that will delay any load of the return address until prior instructions have retired (and thus are not being speculated), or we can harden the address used by the implicit load: the stack pointer.</p>


<p>If we are not using an LFENCE, hardening the stack pointer has an additional benefit: it allows us to pass the predicate state accumulated in this function back to the caller. In the absence of a BCBS attack on the return, the caller will typically be resumed and speculatively executed due to the Return Stack Buffer (RSB) prediction which is very accurate and has a high priority. It is possible that some code from the caller will be executed speculatively even during a BCBS-attacked return until the steering takes effect. Whenever this happens, the caller can recover the (poisoned) predicate state from the stack pointer and continue to harden loads.</p>


<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### hardenValueInRegister() {#a6192a88ae0ffb9aae6d2777f03bc2051}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86SpeculativeLoadHardeningPass::hardenValueInRegister (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Harden a value in a register.</p>


<p>This is the low-level logic to fully harden a value sitting in a register against leaking during speculative execution.</p>


<p>Unlike hardening an address that is used by a load, this routine is required to hide <em>all</em> incoming bits in the register.</p>


<p><span class="doxyComputerOutput">Reg</span> must be a virtual register. Currently, it is required to be a GPR no larger than the predicate state register. FIXME: We should support vector registers here by broadcasting the predicate state.</p>


<p>The new, hardened virtual register is returned. It will have the same register class as <span class="doxyComputerOutput">Reg</span>.</p>


<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### mergePredStateIntoSP() {#a6bf98c3ecbac31ed744d67bd7e1fd6ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::mergePredStateIntoSP (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; Loc, unsigned PredStateReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Takes the current predicate state (in a register) and merges it into the stack pointer.</p>


<p>The state is essentially a single bit, but we merge this in a way that won't form non-canonical pointers and also will be preserved across normal stack adjustments.</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### restoreEFLAGS() {#a57fe992bc7311068a5e174e5115345e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::restoreEFLAGS (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Restore EFLAGS from the provided GPR.</p>


<p>This should be produced by <span class="doxyComputerOutput">saveEFLAGS</span>.</p>


<p>This must be done within the same basic block as the save in order to reliably lower.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### saveEFLAGS() {#a51c88fadd2d858ca48009266fa4f9e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86SpeculativeLoadHardeningPass::saveEFLAGS (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> InsertPt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save EFLAGS into the returned GPR.</p>


<p>This can in turn be restored with <span class="doxyComputerOutput">restoreEFLAGS</span>.</p>


<p>Note that LLVM can only lower very simple patterns of saved and restored EFLAGS registers. The restore should always be within the same basic block as the save so that no PHI nodes are inserted.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### sinkPostLoadHardenedInst() {#a4a2590a4dd70cb8fc910e778999a149d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * X86SpeculativeLoadHardeningPass::sinkPostLoadHardenedInst (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; HardenedInstrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### tracePredStateThroughBlocksAndHarden() {#a83e6c452f7fdc25aeff4b8d56ffa68f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::tracePredStateThroughBlocksAndHarden (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through each of the blocks in the function, hardening everything necessary along the way.</p>


<p>We call this routine once the initial predicate state has been established for each basic block in the function in the SSA updater. This routine traces it through the instructions within each basic block, and for non-returning blocks informs the SSA updater about the final state that lives out of the block. Along the way, it hardens any vulnerable instruction using the currently valid predicate state. We have to do these two things together because the SSA updater only works across blocks. Within a block, we track the current predicate state directly and update it as it changes.</p>


<p>This operates in two passes over each block. First, we analyze the loads in the block to determine which strategy will be used to harden them: hardening the address or hardening the loaded value when loaded into a register amenable to hardening. We have to process these first because the two strategies may interact – later hardening may change what strategy we wish to use. We also will analyze data dependencies between loads and avoid hardening those loads that are data dependent on a load with a hardened address. We also skip hardening loads already behind an LFENCE as that is sufficient to harden them against misspeculation.</p>


<p>Second, we actively trace the predicate state through the block, applying the hardening steps we determined necessary in the first pass as we go.</p>


<p>These two passes are applied to each basic block. We operate one block at a time to simplify reasoning about reachability and sequencing.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### tracePredStateThroughCall() {#a9e3bcfd049a584052d380b5b9f6d5910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::tracePredStateThroughCall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through a call.</p>


<p>There are several layers of this needed to handle the full complexity of calls.</p>


<p>First, we need to send the predicate state into the called function. We do this by merging it into the high bits of the stack pointer.</p>


<p>For tail calls, this is all we need to do.</p>


<p>For calls where we might return and resume the control flow, we need to extract the predicate state from the high bits of the stack pointer after control returns from the called function.</p>


<p>We also need to verify that we intended to return to this location in the code. An attacker might arrange for the processor to mispredict the return to this valid but incorrect return address in the program rather than the correct one. See the paper on this attack, called "ret2spec" by the researchers, here: <a href="https://christian-rossow.de/publications/ret2spec-ccs2018.pdf">https://christian-rossow.de/publications/ret2spec-ccs2018.pdf</a></p>


<p>The way we verify that we returned to the correct location is by preserving the expected return address across the call. One technique involves taking advantage of the red-zone to load the return address from <span class="doxyComputerOutput">8(rsp)</span> where it was left by the RET instruction when it popped <span class="doxyComputerOutput">rsp</span>. Alternatively, we can directly save the address into a register that will be preserved across the call. We compare this intended return address against the address immediately following the call (the observed return address). If these mismatch, we have detected misspeculation and can poison our predicate state.</p>


<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### tracePredStateThroughCFG() {#a561226da60bb592263645c4c2221e2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; MachineInstr *, 16 &gt; X86SpeculativeLoadHardeningPass::tracePredStateThroughCFG (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; BlockCondInfo &gt; Infos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through the CFG, instrumenting each conditional branch such that misspeculation through an edge will poison the predicate state.</p>


<p>Returns the list of inserted CMov instructions so that they can have their uses of the predicate state rewritten into proper SSA form once it is complete.</p>


<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### tracePredStateThroughIndirectBranches() {#a99e2041e476780454dd8421e1ba23bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; MachineInstr *, 16 &gt; X86SpeculativeLoadHardeningPass::tracePredStateThroughIndirectBranches (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/trace">Trace</a> the predicate state through indirect branches, instrumenting them to poison the state if a target is reached that does not match the expected target.</p>


<p>This is designed to mitigate Spectre variant 1 attacks where an indirect branch is trained to predict a particular target and then mispredicts that target in a way that can leak data. Despite using an indirect branch, this is really a variant 1 style attack: it does not steer execution to an arbitrary or attacker controlled address, and it does not require any special code executing next to the victim. This attack can also be mitigated through retpolines, but those require either replacing indirect branches with conditional direct branches or lowering them through a device that blocks speculation. This mitigation can replace these retpoline-style mitigations for jump tables and other indirect branches within a function when variant 2 isn't a risk while allowing limited speculation. Indirect calls, however, cannot be mitigated through this technique without changing the ABI in a fundamental way.</p>


<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### unfoldCallAndJumpLoads() {#abb1705e42db56a885ff72109bae739a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86SpeculativeLoadHardeningPass::unfoldCallAndJumpLoads (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MRI {#a455d25db0312916c89c3b89268a74736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### PS {#ac90994b9a84a001b8c9e5ee90630e184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;PredState&gt; anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::PS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### Subtarget {#ab6d274b65a12e504061a83af5e701001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget* anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::Subtarget = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### TII {#ab25b96ceead471840bc2c0bf4ea9d504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo* anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

### TRI {#a0d888e74c1090f8752b50cbaa7e9e6b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a845bb9b2068e7fd8052fc0e53ed461e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char X86SpeculativeLoadHardeningPass::ID = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pass identification, replacement for typeid.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a>.</p>


<p>Referenced by <a href="#a77a626d52a8457ef92d87b702df1cb7f">X86SpeculativeLoadHardeningPass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp">X86SpeculativeLoadHardening.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
