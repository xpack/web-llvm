---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/m68kmachinefunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `M68kMachineFunctionInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::M68kMachineFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">Target/M68k/M68kMachineFunction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> - This class can be derived from and used by targets to hold private target-specific information for each <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db0e4abcbd3a61ae8a97caf5bb95b76">M68kMachineFunctionInfo</a> (const Function &amp;F, const TargetSubtargetInfo *STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff4fb3a0cf226a4463ad3857dae7013">clone</a> (BumpPtrAllocator &amp;Allocator, MachineFunction &amp;DestMF, const DenseMap&lt; MachineBasicBlock *, MachineBasicBlock * &gt; &amp;Src2DstMBB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>. <a href="#a0ff4fb3a0cf226a4463ad3857dae7013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529520689bb52dc3c4410b6ea710a47b">getRestoreBasePointer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87dcbfef13863161a01d8db51a05498e">setRestoreBasePointer</a> (const MachineFunction *MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c133d4821dfc512bed1c34b00d87dd6">getRestoreBasePointerOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b849a4e86430a01ba304b7315a98793">getCalleeSavedFrameSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b836b0c3e23efb3cc0e13e5ed617317">setCalleeSavedFrameSize</a> (unsigned bytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a5bb0bdf55256f0c03d4630a3cd9e02">getBytesToPopOnReturn</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a31599470ea751229c1860366b8dfc2">setBytesToPopOnReturn</a> (unsigned bytes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ef68da47633f0a90d5e705798470f2">getRAIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89e870424aac745b01a7853c15f0bdb5">setRAIndex</a> (int Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af626f9b51cf8abf865f5f77cd744c1c0">getTCReturnAddrDelta</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e1369ca4a2a8c6a5672c9ec7f0d8dc">setTCReturnAddrDelta</a> (int delta)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae04013478abca2e533730934abc8c809">getGlobalBaseReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2216566f0d7ecb7fbb57b96e2218bc">setGlobalBaseReg</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94870b4b9f109af8b8e5cf0173136485">getVarArgsFrameIndex</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c7de69786e4132a228c81ad41cc9529">setVarArgsFrameIndex</a> (int Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81807104f72851f6f1880e7c4038326">getHasPushSequences</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcd735f28c47f03452d55a1e7cfab990">setHasPushSequences</a> (bool HasPush)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86028cbccf87f3c198d7369ea421d334">getSRetReturnReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266734612e4c2db9bb695074eb5f4226">setSRetReturnReg</a> (unsigned Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81251ef6e89817f030fffdb59e699623">getArgumentStackSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00f0041a1c8d105cebf146c0f62498a">setArgumentStackSize</a> (unsigned size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/forwardedregister">ForwardedRegister</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27c5b88273f83d6a377324105808023c">getForwardedMustTailRegParms</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7844bf2ea28c11f4d086821ede16a3ee">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">signed char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470324884e0bf545e5a52f7f433b2669">RestoreBasePointerOffset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Non-zero if the function has base pointer and makes call to llvm.eh.sjlj.setjmp. <a href="#a470324884e0bf545e5a52f7f433b2669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3bc24e13dcbb295c116246665e7dda9">CalleeSavedFrameSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size of the callee-saved register portion of the stack frame in bytes. <a href="#aa3bc24e13dcbb295c116246665e7dda9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74186e01f16d2afaee6beec3af7c7fee">BytesToPopOnReturn</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of bytes function pops on return (in addition to the space used by the return address). <a href="#a74186e01f16d2afaee6beec3af7c7fee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d5f79762eb4470988edcee04679da21">ReturnAddrIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for return slot. <a href="#a6d5f79762eb4470988edcee04679da21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0d1517a10f10289267780a6eb45fb50">TailCallReturnAddrDelta</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes by which return address stack slot is moved as the result of tail call optimization. <a href="#ab0d1517a10f10289267780a6eb45fb50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9492a00b246848ab0d3c1ab7b297dbc6">GlobalBaseReg</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>keeps track of the virtual register initialized for use as the global base register. <a href="#a9492a00b246848ab0d3c1ab7b297dbc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49467a3c61136b0d1b07193f7d1b4906">VarArgsFrameIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FrameIndex for start of varargs area. <a href="#a49467a3c61136b0d1b07193f7d1b4906">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9342b684a3c6c215e8cac96497e3feef">HasPushSequences</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of whether this function uses sequences of pushes to pass function parameters. <a href="#a9342b684a3c6c215e8cac96497e3feef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3654e9c0f7764060e103d0c6776a708">SRetReturnReg</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Some subtargets require that sret lowering includes returning the value of the returned struct in a register. <a href="#ad3654e9c0f7764060e103d0c6776a708">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/forwardedregister">ForwardedRegister</a>, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad54f44abfa5d1254e238969366881ca5">ForwardedMustTailRegParms</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of virtual and physical registers that must be forwarded to every musttail call. <a href="#ad54f44abfa5d1254e238969366881ca5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab62ee1cb3f57ebc4c83fc2adf84c8b12">ArgumentStackSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of bytes on stack consumed by the arguments being passed on the stack. <a href="#ab62ee1cb3f57ebc4c83fc2adf84c8b12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### M68kMachineFunctionInfo() {#a2db0e4abcbd3a61ae8a97caf5bb95b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::M68kMachineFunctionInfo::M68kMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a0ff4fb3a0cf226a4463ad3857dae7013">clone</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a0ff4fb3a0cf226a4463ad3857dae7013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * M68kMachineFunctionInfo::clone (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; DestMF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; &amp; Src2DstMBB)</td>
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

<p>Make a functionally equivalent copy of this <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> in <span class="doxyComputerOutput">MF</span>.</p>


<p>This requires remapping <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> references from the original parent to values in the new function. Targets may assume that virtual register and frame index values are preserved in the new function.</p>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-cpp">M68kMachineFunction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac31b21febeefe69aaddea3541dae45e1">llvm::MachineFunction::cloneInfo</a> and <a href="#a2db0e4abcbd3a61ae8a97caf5bb95b76">M68kMachineFunctionInfo</a>.</p>

</div>
</div>

### getArgumentStackSize() {#a81251ef6e89817f030fffdb59e699623}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::getArgumentStackSize ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### getBytesToPopOnReturn() {#a6a5bb0bdf55256f0c03d4630a3cd9e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::getBytesToPopOnReturn ()</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### getCalleeSavedFrameSize() {#a4b849a4e86430a01ba304b7315a98793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::getCalleeSavedFrameSize ()</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getForwardedMustTailRegParms() {#a27c5b88273f83d6a377324105808023c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; ForwardedRegister &gt; &amp; llvm::M68kMachineFunctionInfo::getForwardedMustTailRegParms ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### getGlobalBaseReg() {#ae04013478abca2e533730934abc8c809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::getGlobalBaseReg ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a044e17811fc0aef16bcbf9b59e41b421">llvm::M68kInstrInfo::getGlobalBaseReg</a>.</p>

</div>
</div>

### getHasPushSequences() {#ab81807104f72851f6f1880e7c4038326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kMachineFunctionInfo::getHasPushSequences ()</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a9a9a690dd5678ad91fe6622af79116fd">llvm::M68kFrameLowering::eliminateCallFramePseudoInstr</a>.</p>

</div>
</div>

### getRAIndex() {#a43ef68da47633f0a90d5e705798470f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::getRAIndex ()</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### getRestoreBasePointer() {#a529520689bb52dc3c4410b6ea710a47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kMachineFunctionInfo::getRestoreBasePointer ()</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getRestoreBasePointerOffset() {#a3c133d4821dfc512bed1c34b00d87dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::getRestoreBasePointerOffset ()</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getSRetReturnReg() {#a86028cbccf87f3c198d7369ea421d334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::getSRetReturnReg ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### getTCReturnAddrDelta() {#af626f9b51cf8abf865f5f77cd744c1c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::getTCReturnAddrDelta ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3b9c6a6d8deeb4b38fe15c4bbfcfaced">llvm::M68kFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a16d9aef1065a0997fe2ac4b560ca9cce">llvm::M68kFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a27812f7473acb8b3398abc5a297ea082">llvm::M68kFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a> and <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a7a7d0ca18a51d0d4829fb467deed15e9">llvm::M68kFrameLowering::getFrameIndexReference</a>.</p>

</div>
</div>

### getVarArgsFrameIndex() {#a94870b4b9f109af8b8e5cf0173136485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::getVarArgsFrameIndex ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### setArgumentStackSize() {#ae00f0041a1c8d105cebf146c0f62498a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setArgumentStackSize (unsigned size)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### setBytesToPopOnReturn() {#a6a31599470ea751229c1860366b8dfc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setBytesToPopOnReturn (unsigned bytes)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### setCalleeSavedFrameSize() {#a8b836b0c3e23efb3cc0e13e5ed617317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setCalleeSavedFrameSize (unsigned bytes)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#ab562d636c0f4809fd64bb0bb674916e8">llvm::M68kFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### setGlobalBaseReg() {#a9d2216566f0d7ecb7fbb57b96e2218bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setGlobalBaseReg (unsigned Reg)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a044e17811fc0aef16bcbf9b59e41b421">llvm::M68kInstrInfo::getGlobalBaseReg</a>.</p>

</div>
</div>

### setHasPushSequences() {#adcd735f28c47f03452d55a1e7cfab990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setHasPushSequences (bool HasPush)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### setRAIndex() {#a89e870424aac745b01a7853c15f0bdb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setRAIndex (int Index)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### setRestoreBasePointer() {#a87dcbfef13863161a01d8db51a05498e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setRestoreBasePointer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### setSRetReturnReg() {#a266734612e4c2db9bb695074eb5f4226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setSRetReturnReg (unsigned Reg)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### setTCReturnAddrDelta() {#ae9e1369ca4a2a8c6a5672c9ec7f0d8dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setTCReturnAddrDelta (int delta)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### setVarArgsFrameIndex() {#a0c7de69786e4132a228c81ad41cc9529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::M68kMachineFunctionInfo::setVarArgsFrameIndex (int Index)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a7844bf2ea28c11f4d086821ede16a3ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kMachineFunctionInfo::anchor ()</td>
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



<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-cpp">M68kMachineFunction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArgumentStackSize {#ab62ee1cb3f57ebc4c83fc2adf84c8b12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::ArgumentStackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes on stack consumed by the arguments being passed on the stack.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### BytesToPopOnReturn {#a74186e01f16d2afaee6beec3af7c7fee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::BytesToPopOnReturn = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of bytes function pops on return (in addition to the space used by the return address).</p>


<p>Used on windows platform for stdcall &amp; fastcall name decoration</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### CalleeSavedFrameSize {#aa3bc24e13dcbb295c116246665e7dda9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::CalleeSavedFrameSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size of the callee-saved register portion of the stack frame in bytes.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### ForwardedMustTailRegParms {#ad54f44abfa5d1254e238969366881ca5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ForwardedRegister, 1&gt; llvm::M68kMachineFunctionInfo::ForwardedMustTailRegParms</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of virtual and physical registers that must be forwarded to every musttail call.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### GlobalBaseReg {#a9492a00b246848ab0d3c1ab7b297dbc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::GlobalBaseReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>keeps track of the virtual register initialized for use as the global base register.</p>


<p>This is used for PIC in some PIC relocation models.</p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### HasPushSequences {#a9342b684a3c6c215e8cac96497e3feef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::M68kMachineFunctionInfo::HasPushSequences = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of whether this function uses sequences of pushes to pass function parameters.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### RestoreBasePointerOffset {#a470324884e0bf545e5a52f7f433b2669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">signed char llvm::M68kMachineFunctionInfo::RestoreBasePointerOffset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Non-zero if the function has base pointer and makes call to llvm.eh.sjlj.setjmp.</p>


<p>When non-zero, the value is a displacement from the frame pointer to a slot where the base pointer is stashed.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### ReturnAddrIndex {#a6d5f79762eb4470988edcee04679da21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::ReturnAddrIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for return slot.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### SRetReturnReg {#ad3654e9c0f7764060e103d0c6776a708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::M68kMachineFunctionInfo::SRetReturnReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Some subtargets require that sret lowering includes returning the value of the returned struct in a register.</p>


<p>This field holds the virtual register into which the sret argument is passed.</p>


<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### TailCallReturnAddrDelta {#ab0d1517a10f10289267780a6eb45fb50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::TailCallReturnAddrDelta = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of bytes by which return address stack slot is moved as the result of tail call optimization.</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

### VarArgsFrameIndex {#a49467a3c61136b0d1b07193f7d1b4906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::M68kMachineFunctionInfo::VarArgsFrameIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FrameIndex for start of varargs area.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-cpp">M68kMachineFunction.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kmachinefunction-h">M68kMachineFunction.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
