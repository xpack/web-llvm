---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functionloweringinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionLoweringInfo` Class

<p><a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> - This contains information that is global to a function that is used when lowering a region of the function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionLoweringInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">llvm/CodeGen/FunctionLoweringInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048f1293156d31b62bd6622398a165a9">StatepointSpillMapTy</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/statepointrelocationrecord">StatepointRelocationRecord</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of each value which was relocated and the strategy used to relocate that value. <a href="#a048f1293156d31b62bd6622398a165a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad89b3db56d061cd3cf70ad2a94c66b8a">getValueFromVirtualReg</a> (Register Vreg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is called from TargetLowerinInfo::isSDNodeSourceOfDivergence to get the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> corresponding to the live-in virtual register. <a href="#ad89b3db56d061cd3cf70ad2a94c66b8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971f804e98558726a547fa8fefe28a11">set</a> (const Function &amp;Fn, MachineFunction &amp;MF, SelectionDAG *DAG)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>set - Initialize this <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> with the given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> and its associated <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#a971f804e98558726a547fa8fefe28a11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1281235664d14beac83662b9f943e6d1">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clear - Clear out all the function-specific state. <a href="#a1281235664d14beac83662b9f943e6d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54f8a969772167ed351abae3f26303f3">isExportedInst</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isExportedInst - Return true if the specified value is an instruction exported from its block. <a href="#a54f8a969772167ed351abae3f26303f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14a2bf30885cc5b91b86a564759980bb">getMBB</a> (const BasicBlock *BB) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addc080407660a5304ac3b7005d242bd2">CreateReg</a> (MVT VT, bool isDivergent=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateReg - Allocate a single virtual register for the given type. <a href="#addc080407660a5304ac3b7005d242bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9ae2c8bd9d78d63eede987561ba39ee">CreateRegs</a> (Type *Ty, bool isDivergent=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateRegs - Allocate the appropriate number of virtual registers of the correctly promoted or expanded types. <a href="#ab9ae2c8bd9d78d63eede987561ba39ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6acfcd7e0cfb4ea7791d581e7f8dbd9d">InitializeRegForValue</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60dfda975fe4068ff59554303033a9a3">GetLiveOutRegInfo</a> (Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetLiveOutRegInfo - Gets <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a register, returning NULL if the register is a PHI destination and the PHI's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> is not valid. <a href="#a60dfda975fe4068ff59554303033a9a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ba73377df4268433b190a98516ce8d">GetLiveOutRegInfo</a> (Register Reg, unsigned BitWidth)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetLiveOutRegInfo - Gets <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a register, returning NULL if the register is a PHI destination and the PHI's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> is not valid. <a href="#a53ba73377df4268433b190a98516ce8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5afb7d50f639285c9ef082439615915e">AddLiveOutRegInfo</a> (Register Reg, unsigned NumSignBits, const KnownBits &amp;Known)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddLiveOutRegInfo - Adds <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a register. <a href="#a5afb7d50f639285c9ef082439615915e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acada979e9424b6f61142bbca85a0fea0">ComputePHILiveOutRegInfo</a> (const PHINode *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ComputePHILiveOutRegInfo - Compute <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a PHI's destination register based on the <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> of its operands. <a href="#acada979e9424b6f61142bbca85a0fea0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39bc44baeb40615967a3ce797fb27900">InvalidatePHILiveOutRegInfo</a> (const PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InvalidatePHILiveOutRegInfo - Invalidates a PHI's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a>, to be called when a block is visited before all of its predecessors. <a href="#a39bc44baeb40615967a3ce797fb27900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2752e8fd3a00aa8c955da610c36b90a3">setArgumentFrameIndex</a> (const Argument *A, int FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setArgumentFrameIndex - <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> frame index for the byval argument. <a href="#a2752e8fd3a00aa8c955da610c36b90a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4adbd2ebdab9c844ce0443c43c3ee16d">getArgumentFrameIndex</a> (const Argument *A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getArgumentFrameIndex - Get frame index for the byval argument. <a href="#a4adbd2ebdab9c844ce0443c43c3ee16d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeed2af86c53eb65a738276c01feb4933">getCatchPadExceptionPointerVReg</a> (const Value *CPI, const TargetRegisterClass *RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc1221aa25a478c9c847f14deb840de0">setCurrentCallSite</a> (unsigned Site)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the call site currently being processed. <a href="#adc1221aa25a478c9c847f14deb840de0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcad8435d25e74759d97489fa0c31883">getCurrentCallSite</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the call site currently being processed, if any. Return zero if none. <a href="#abcad8435d25e74759d97489fa0c31883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6af88ef964b6f03824a35fa0081efa9">Fn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9287d39f216ac61b351d95a4f7e3df3">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda780c93aae358f7ee00c01081ee840">RegInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo">BranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021952a3b657f6321d050112563886c4">BPI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a00a2f5a62b5d5d5b6b0e143c4d30041f">UniformityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d7756207368edfc6415f7f180836bd">UA</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade69181df61b7b2bc7287062cf0847ce">CanLowerReturn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CanLowerReturn - true iff the function's return value can be lowered to registers. <a href="#ade69181df61b7b2bc7287062cf0847ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758d6756fc413f99be3028b9068c8e06">SplitCSR</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if part of the CSRs will be handled via explicit copies. <a href="#a758d6756fc413f99be3028b9068c8e06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f392642c7a9d07fc516fcfa697d05c7">DemoteRegister</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DemoteRegister - if CanLowerReturn is false, DemoteRegister is a vreg allocated to hold a pointer to the hidden sret parameter. <a href="#a1f392642c7a9d07fc516fcfa697d05c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2d89ef8260d2242a6f565d997c1616">MBBMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from LLVM basic block number to their machine block. <a href="#acb2d89ef8260d2242a6f565d997c1616">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a> - Since we emit code for the function a basic block at a time, we must remember which virtual registers hold the values for cross-basic-block values. <a href="#a7fe2a1d04fbf581308aa60fa34e22069">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc73312d3b0c4b5a5b4b1789c72ae94c">VirtReg2Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VirtReg2Value map is needed by the Divergence Analysis driven instruction selection. <a href="#adc73312d3b0c4b5a5b4b1789c72ae94c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af772f4041cf809781625c00a0bffe7ed">CatchPadExceptionPointers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Track virtual registers created for exception pointers. <a href="#af772f4041cf809781625c00a0bffe7ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="#a048f1293156d31b62bd6622398a165a9">StatepointSpillMapTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a460bac4fe51e0dcd08f1fb328005926d">StatepointRelocationMaps</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec121cc6c5c5141f5ac46f101727e8a">StaticAllocaMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StaticAllocaMap - Keep track of frame indices for fixed sized allocas in the entry block. <a href="#a3ec121cc6c5c5141f5ac46f101727e8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec33929a5691960c10bca5c8ec49fe6">ByValArgFrameIndexMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ByValArgFrameIndexMap - Keep track of frame indices for byval arguments. <a href="#a9ec33929a5691960c10bca5c8ec49fe6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7855aa1fdda952bb8b25a41df0cf976">ArgDbgValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ArgDbgValues - A list of DBG_VALUE instructions created during isel for function arguments that are inserted after scheduling is completed. <a href="#aa7855aa1fdda952bb8b25a41df0cf976">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a67e668695f8af2d2fcf14ce4a9f9ad">DescribedArgs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitvector with a bit set if corresponding argument is described in ArgDbgValues. <a href="#a3a67e668695f8af2d2fcf14ce4a9f9ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa749dd21cbc2b9c9dc1482bc714aac6e">RegFixups</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RegFixups - Registers which need to be replaced after isel is done. <a href="#aa749dd21cbc2b9c9dc1482bc714aac6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6410ef3df4aff6a61a5dbbf252f3a0">RegsWithFixups</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 50 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9691f14813e0540e6a1c90cfdad39df3">StatepointStackSlots</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>StatepointStackSlots - A list of temporary stack slots (frame indices) used to spill values at a statepoint. <a href="#a9691f14813e0540e6a1c90cfdad39df3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9893077f1825192ca0f3d173afefb573">MBB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MBB - The current block. <a href="#a9893077f1825192ca0f3d173afefb573">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90b6dd55afe6936ce5854c71baadbf92">InsertPt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MBB - The current insert position inside the current block. <a href="#a90b6dd55afe6936ce5854c71baadbf92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110">ISD::NodeType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed51a923085b2a92ae822375e5ca6913">PreferredExtendType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the preferred extend type (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">ISD::SIGN_EXTEND</a> or <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">ISD::ZERO_EXTEND</a>) for a value. <a href="#aed51a923085b2a92ae822375e5ca6913">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d79b9982e5b7c8f3e2a181727a35778">VisitedBBs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of basic blocks visited thus far by instruction selection. <a href="#a2d79b9982e5b7c8f3e2a181727a35778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d5184cf5e487012782adccecbc2dd6">PHINodesToUpdate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PHINodesToUpdate - A list of phi instructions whose operand list will be updated after processing the current basic block. <a href="#a99d5184cf5e487012782adccecbc2dd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0200bc03523f2fed22a34edeb8d5d4">OrigNumPHINodesToUpdate</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a716439884c5e6ea61ce2343378dae844">ExceptionPointerVirtReg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the current MBB is a landing pad, the exception pointer and exception selector registers are copied into these virtual registers by SelectionDAGISel::PrepareEHLandingPad(). <a href="#a716439884c5e6ea61ce2343378dae844">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa783b39d93936bd28d34abee51edb2c3">ExceptionSelectorVirtReg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a499554ae812b80edc43cbcccd9e7f1ca">CurCallSite</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current call site index being processed, if any. 0 if none. <a href="#a499554ae812b80edc43cbcccd9e7f1ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst">DbgDeclareInst</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa8e84e7d5f268d5bbc8bd93d497867">PreprocessedDbgDeclares</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of dbg.declare instructions handled after argument lowering and before ISel proper. <a href="#a7fa8e84e7d5f268d5bbc8bd93d497867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord">DbgVariableRecord</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f535e2de728fc1a44caffba9eeea9a7">PreprocessedDVRDeclares</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ddcd95fbba28a3d277b9514757f9d6c">LiveOutRegInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LiveOutRegInfo - Information about live out vregs. <a href="#a9ddcd95fbba28a3d277b9514757f9d6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> - This contains information that is global to a function that is used when lowering a region of the function.</p>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### StatepointSpillMapTy {#a048f1293156d31b62bd6622398a165a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FunctionLoweringInfo::StatepointSpillMapTy = 
    DenseMap&lt;const Value *, StatepointRelocationRecord&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of each value which was relocated and the strategy used to relocate that value.</p>


<p>This information is required when visiting gc.relocates which may appear in following blocks.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddLiveOutRegInfo() {#a5afb7d50f639285c9ef082439615915e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionLoweringInfo::AddLiveOutRegInfo (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned NumSignBits, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/knownbits">KnownBits</a> &amp; Known)</td>
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

<p>AddLiveOutRegInfo - Adds <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a register.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a28cf355963391ab8781b2347d495553d">llvm::KnownBits::isUnknown</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#ac49dfd777da8c8caee8f3d6370ef14ea">llvm::FunctionLoweringInfo::LiveOutInfo::Known</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a651904591143e71c02a94dca2659fc8e">llvm::FunctionLoweringInfo::LiveOutInfo::NumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### clear() {#a1281235664d14beac83662b9f943e6d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionLoweringInfo::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clear - Clear out all the function-specific state.</p>


<p>This returns this <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> to an empty state, ready to be used for a different function.</p>


<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="#aa7855aa1fdda952bb8b25a41df0cf976">ArgDbgValues</a>, <a href="#a9ec33929a5691960c10bca5c8ec49fe6">ByValArgFrameIndexMap</a>, <a href="#a3a67e668695f8af2d2fcf14ce4a9f9ad">DescribedArgs</a>, <a href="#acb2d89ef8260d2242a6f565d997c1616">MBBMap</a>, <a href="#aed51a923085b2a92ae822375e5ca6913">PreferredExtendType</a>, <a href="#a7fa8e84e7d5f268d5bbc8bd93d497867">PreprocessedDbgDeclares</a>, <a href="#a0f535e2de728fc1a44caffba9eeea9a7">PreprocessedDVRDeclares</a>, <a href="#aa749dd21cbc2b9c9dc1482bc714aac6e">RegFixups</a>, <a href="#a1d6410ef3df4aff6a61a5dbbf252f3a0">RegsWithFixups</a>, <a href="#a460bac4fe51e0dcd08f1fb328005926d">StatepointRelocationMaps</a>, <a href="#a9691f14813e0540e6a1c90cfdad39df3">StatepointStackSlots</a>, <a href="#a3ec121cc6c5c5141f5ac46f101727e8a">StaticAllocaMap</a>, <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a>, <a href="#adc73312d3b0c4b5a5b4b1789c72ae94c">VirtReg2Value</a> and <a href="#a2d79b9982e5b7c8f3e2a181727a35778">VisitedBBs</a>.</p>

</div>
</div>

### ComputePHILiveOutRegInfo() {#acada979e9424b6f61142bbca85a0fea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionLoweringInfo::ComputePHILiveOutRegInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ComputePHILiveOutRegInfo - Compute <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a PHI's destination register based on the <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> of its operands.</p>

<p>Declaration at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aca1fd00f3ab63ec8f0f1ccc2093a9f6d">llvm::PHINode::getIncomingValue</a>, <a href="#a60dfda975fe4068ff59554303033a9a3">GetLiveOutRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#aef51af4b490af6b3bf2dfbc8737a8f9f">llvm::PHINode::getNumIncomingValues</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8924f4d542442eecf3aac41a0bd61fa3">llvm::APInt::getNumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a76e45a40f2f0b5b09132d1de119765e8">llvm::KnownBits::intersectWith</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a45db7e23083b4babe630353f2e2a2510">llvm::FunctionLoweringInfo::LiveOutInfo::IsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#ac49dfd777da8c8caee8f3d6370ef14ea">llvm::FunctionLoweringInfo::LiveOutInfo::Known</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a066220c7a472d8793de64a0ad23487d2">llvm::KnownBits::makeConstant</a>, <a href="#ac9287d39f216ac61b351d95a4f7e3df3">MF</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a651904591143e71c02a94dca2659fc8e">llvm::FunctionLoweringInfo::LiveOutInfo::NumSignBits</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a>, <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>

</div>
</div>

### CreateReg() {#addc080407660a5304ac3b7005d242bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FunctionLoweringInfo::CreateReg (<a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, bool isDivergent=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CreateReg - Allocate a single virtual register for the given type.</p>

<p>Declaration at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="#adda780c93aae358f7ee00c01081ee840">RegInfo</a> and <a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a>.</p>


<p>Referenced by <a href="#ab9ae2c8bd9d78d63eede987561ba39ee">CreateRegs</a>.</p>

</div>
</div>

### CreateRegs() {#a02e2a094addb0070a73d9c9d05098246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FunctionLoweringInfo::CreateRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a>, <a href="#ac9287d39f216ac61b351d95a4f7e3df3">MF</a>, <a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a> and <a href="#a44d7756207368edfc6415f7f180836bd">UA</a>.</p>


<p>Referenced by <a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a> and <a href="#a6acfcd7e0cfb4ea7791d581e7f8dbd9d">InitializeRegForValue</a>.</p>

</div>
</div>

### CreateRegs() {#ab9ae2c8bd9d78d63eede987561ba39ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FunctionLoweringInfo::CreateRegs (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, bool isDivergent=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CreateRegs - Allocate the appropriate number of virtual registers of the correctly promoted or expanded types.</p>


<p>Assign these registers consecutive vreg numbers and return the first assigned number.</p>


<p>In the case that the given value has struct or array type, this function will assign registers for each member or element.</p>


<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="#addc080407660a5304ac3b7005d242bd2">CreateReg</a>, <a href="#ac9287d39f216ac61b351d95a4f7e3df3">MF</a> and <a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a>.</p>

</div>
</div>

### getArgumentFrameIndex() {#a4adbd2ebdab9c844ce0443c43c3ee16d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FunctionLoweringInfo::getArgumentFrameIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * A)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getArgumentFrameIndex - Get frame index for the byval argument.</p>


<p>If the argument does not have any assigned frame index then 0 is returned.</p>


<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a9ec33929a5691960c10bca5c8ec49fe6">ByValArgFrameIndexMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>.</p>

</div>
</div>

### getCatchPadExceptionPointerVReg() {#aeed2af86c53eb65a738276c01feb4933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FunctionLoweringInfo::getCatchPadExceptionPointerVReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * CPI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af772f4041cf809781625c00a0bffe7ed">CatchPadExceptionPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac9287d39f216ac61b351d95a4f7e3df3">MF</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### getCurrentCallSite() {#abcad8435d25e74759d97489fa0c31883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::getCurrentCallSite ()</td>
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

<p>Get the call site currently being processed, if any. Return zero if none.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Reference <a href="#a499554ae812b80edc43cbcccd9e7f1ca">CurCallSite</a>.</p>

</div>
</div>

### GetLiveOutRegInfo() {#a60dfda975fe4068ff59554303033a9a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LiveOutInfo * llvm::FunctionLoweringInfo::GetLiveOutRegInfo (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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

<p>GetLiveOutRegInfo - Gets <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a register, returning NULL if the register is a PHI destination and the PHI's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> is not valid.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a45db7e23083b4babe630353f2e2a2510">llvm::FunctionLoweringInfo::LiveOutInfo::IsValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#acada979e9424b6f61142bbca85a0fea0">ComputePHILiveOutRegInfo</a>.</p>

</div>
</div>

### GetLiveOutRegInfo() {#a53ba73377df4268433b190a98516ce8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionLoweringInfo::LiveOutInfo * FunctionLoweringInfo::GetLiveOutRegInfo (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetLiveOutRegInfo - Gets <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> for a register, returning NULL if the register is a PHI destination and the PHI's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> is not valid.</p>


<p>If the register's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a> is for a smaller bit width, it is extended to the larger bit width by zero extension. The bit width must be no smaller than the <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a>'s existing bit width.</p>


<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac6661654e5ce1b32651508eec50b6d58">llvm::KnownBits::anyext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#a4fdc09049a61f952b5d52788dbd2f69b">llvm::KnownBits::getBitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a45db7e23083b4babe630353f2e2a2510">llvm::FunctionLoweringInfo::LiveOutInfo::IsValid</a>, <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#ac49dfd777da8c8caee8f3d6370ef14ea">llvm::FunctionLoweringInfo::LiveOutInfo::Known</a> and <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo/#a651904591143e71c02a94dca2659fc8e">llvm::FunctionLoweringInfo::LiveOutInfo::NumSignBits</a>.</p>

</div>
</div>

### getMBB() {#a14a2bf30885cc5b91b86a564759980bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock * llvm::FunctionLoweringInfo::getMBB (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0bf3a7e9bff209ef9f8d2eb194196848">llvm::BasicBlock::getNumber</a> and <a href="#acb2d89ef8260d2242a6f565d997c1616">MBBMap</a>.</p>


<p>Referenced by <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### getValueFromVirtualReg() {#ad89b3db56d061cd3cf70ad2a94c66b8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * FunctionLoweringInfo::getValueFromVirtualReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Vreg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is called from TargetLowerinInfo::isSDNodeSourceOfDivergence to get the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> corresponding to the live-in virtual register.</p>

<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="#aa6af88ef964b6f03824a35fa0081efa9">Fn</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a>, <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a> and <a href="#adc73312d3b0c4b5a5b4b1789c72ae94c">VirtReg2Value</a>.</p>

</div>
</div>

### InitializeRegForValue() {#a6acfcd7e0cfb4ea7791d581e7f8dbd9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FunctionLoweringInfo::InitializeRegForValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>, <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a> and <a href="#adc73312d3b0c4b5a5b4b1789c72ae94c">VirtReg2Value</a>.</p>


<p>Referenced by <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### InvalidatePHILiveOutRegInfo() {#a39bc44baeb40615967a3ce797fb27900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionLoweringInfo::InvalidatePHILiveOutRegInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
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

<p>InvalidatePHILiveOutRegInfo - Invalidates a PHI's <a href="/web-llvm/docs/api/structs/llvm/functionloweringinfo/liveoutinfo">LiveOutInfo</a>, to be called when a block is visited before all of its predecessors.</p>

<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a>.</p>

</div>
</div>

### isExportedInst() {#a54f8a969772167ed351abae3f26303f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionLoweringInfo::isExportedInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>isExportedInst - Return true if the specified value is an instruction exported from its block.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Reference <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a>.</p>

</div>
</div>

### set() {#a971f804e98558726a547fa8fefe28a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionLoweringInfo::set (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; Fn, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> * DAG)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>set - Initialize this <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> with the given <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> and its associated <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afcc6ddcd882a86a3d6028e2530b4d4cc">llvm::calculateClrEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa75cdd420a3ce670e2c3b61046f2b8a7">llvm::calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3fd09aad409fbbe332f6e29711d7698">llvm::calculateWasmEHInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4547a0e8cb23afe1f8767916fd173920">llvm::calculateWinCXXEHStateNumbers</a>, <a href="#ade69181df61b7b2bc7287062cf0847ce">CanLowerReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d508f23e2580095561902c39911fb9b">llvm::classifyEHPersonality</a>, <a href="/web-llvm/docs/api/structs/llvm/cxxunwindmapentry/#a7ee3503343cf5882acdc24630589b876">llvm::CxxUnwindMapEntry::Cleanup</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#a33a3829e787ffc244c98cd78e51e5b5e">llvm::WinEHFuncInfo::ClrEHUnwindMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa05b0e25c98ba4300ca28989a35dab72a">llvm::CoreCLR</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#ae253a5107fc357c27ab3292af4dbb353">llvm::WinEHFuncInfo::CxxUnwindMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#aa6af88ef964b6f03824a35fa0081efa9">Fn</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a82dd10b626a629b9bb7d32d53a8e0884">llvm::MachineFunction::getDataLayout</a>, <a href="#a14a2bf30885cc5b91b86a564759980bb">getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac35eb465b1587df5f61aa7f7a7fce6f7">llvm::SelectionDAG::getOptLevel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp/#a2d03d74d7d3ea3a7ae3986e726bdace4">getPreferredExtendForValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a74d93035f53f5e8c2aaea5a8f307972d">llvm::TargetFrameLowering::getStackAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a5fea26e6022c2ee4c4e5a9c74d6dbbb3">llvm::TargetFrameLowering::getStackIDForScalableVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac2bf8367cd8ee0cffc5eb41c5075567a">llvm::SelectionDAG::getUniformityInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/structs/llvm/clrehunwindmapentry/#a62529f10591fd4e748c380c8f91b49ca">llvm::ClrEHUnwindMapEntry::Handler</a>, <a href="/web-llvm/docs/api/structs/llvm/winehtryblockmapentry/#a203f60eaca27055d5b7395fca270037e">llvm::WinEHTryBlockMapEntry::HandlerArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a6acfcd7e0cfb4ea7791d581e7f8dbd9d">InitializeRegForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c9fb92464f96c0e0f326d624e82eab">llvm::isAsynchronousEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34adf39e7f7e158f2ccacae6d4446197322">llvm::InlineAsm::isClobber</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa014490a40c9286ee7e026a2f579eea9">llvm::isFuncletEHPersonality</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a5eb659c968445b7676c09119894ef4ff">llvm::TargetFrameLowering::isStackRealignable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp/#aec1de31cd4bfbbbf00d2903ecae5cbba">isUsedOutsideOfDefiningBlock</a>, <a href="#a9893077f1825192ca0f3d173afefb573">MBB</a>, <a href="#acb2d89ef8260d2242a6f565d997c1616">MBBMap</a>, <a href="#ac9287d39f216ac61b351d95a4f7e3df3">MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aab34bedfd8d86f0adbefe4ae0e708f428">llvm::MSVC_CXX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#aed51a923085b2a92ae822375e5ca6913">PreferredExtendType</a>, <a href="#adda780c93aae358f7ee00c01081ee840">RegInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#a2055c2e7a5444cfd152906a25dbf77ad">llvm::WinEHFuncInfo::SEHUnwindMap</a>, <a href="/web-llvm/docs/api/structs/llvm/wasmehfuncinfo/#af88cf4d6f8fb68dd00ba4875609c2af2">llvm::WasmEHFuncInfo::SrcToUnwindDest</a>, <a href="#a3ec121cc6c5c5141f5ac46f101727e8a">StaticAllocaMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="#ad6fd4272e74d05a2450311a32099b5f5">TLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/winehfuncinfo/#a704147adbd0b4b79d33d444f76e8617c">llvm::WinEHFuncInfo::TryBlockMap</a>, <a href="#a44d7756207368edfc6415f7f180836bd">UA</a>, <a href="/web-llvm/docs/api/structs/llvm/wasmehfuncinfo/#a074a38ccf278711929e1c72d933bfc17">llvm::WasmEHFuncInfo::UnwindDestToSrcs</a>, <a href="#a7fe2a1d04fbf581308aa60fa34e22069">ValueMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d56157a385f8cd7d3e54ed87da1ba6aa7939c43653700c52daa7a68a575c3ec5">llvm::Wasm_CXX</a>.</p>

</div>
</div>

### setArgumentFrameIndex() {#a2752e8fd3a00aa8c955da610c36b90a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FunctionLoweringInfo::setArgumentFrameIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> * A, int FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setArgumentFrameIndex - <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> frame index for the byval argument.</p>


<p>This overrides previous frame index entry for this argument, if any.</p>


<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a9ec33929a5691960c10bca5c8ec49fe6">ByValArgFrameIndexMap</a>.</p>

</div>
</div>

### setCurrentCallSite() {#adc1221aa25a478c9c847f14deb840de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionLoweringInfo::setCurrentCallSite (unsigned Site)</td>
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

<p>Set the call site currently being processed.</p>

<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Reference <a href="#a499554ae812b80edc43cbcccd9e7f1ca">CurCallSite</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ArgDbgValues {#aa7855aa1fdda952bb8b25a41df0cf976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 8&gt; llvm::FunctionLoweringInfo::ArgDbgValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ArgDbgValues - A list of DBG_VALUE instructions created during isel for function arguments that are inserted after scheduling is completed.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

### BPI {#a021952a3b657f6321d050112563886c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BranchProbabilityInfo* llvm::FunctionLoweringInfo::BPI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### ByValArgFrameIndexMap {#a9ec33929a5691960c10bca5c8ec49fe6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Argument*, int&gt; llvm::FunctionLoweringInfo::ByValArgFrameIndexMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ByValArgFrameIndexMap - Keep track of frame indices for byval arguments.</p>

<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>, <a href="#a4adbd2ebdab9c844ce0443c43c3ee16d">getArgumentFrameIndex</a> and <a href="#a2752e8fd3a00aa8c955da610c36b90a3">setArgumentFrameIndex</a>.</p>

</div>
</div>

### CanLowerReturn {#ade69181df61b7b2bc7287062cf0847ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionLoweringInfo::CanLowerReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CanLowerReturn - true iff the function's return value can be lowered to registers.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### CatchPadExceptionPointers {#af772f4041cf809781625c00a0bffe7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, Register&gt; llvm::FunctionLoweringInfo::CatchPadExceptionPointers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Track virtual registers created for exception pointers.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#aeed2af86c53eb65a738276c01feb4933">getCatchPadExceptionPointerVReg</a>.</p>

</div>
</div>

### CurCallSite {#a499554ae812b80edc43cbcccd9e7f1ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::CurCallSite = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current call site index being processed, if any. 0 if none.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#abcad8435d25e74759d97489fa0c31883">getCurrentCallSite</a> and <a href="#adc1221aa25a478c9c847f14deb840de0">setCurrentCallSite</a>.</p>

</div>
</div>

### DemoteRegister {#a1f392642c7a9d07fc516fcfa697d05c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::FunctionLoweringInfo::DemoteRegister</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DemoteRegister - if CanLowerReturn is false, DemoteRegister is a vreg allocated to hold a pointer to the hidden sret parameter.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### DescribedArgs {#a3a67e668695f8af2d2fcf14ce4a9f9ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector llvm::FunctionLoweringInfo::DescribedArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bitvector with a bit set if corresponding argument is described in ArgDbgValues.</p>


<p>Using arg numbers according to <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> numbering.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

### ExceptionPointerVirtReg {#a716439884c5e6ea61ce2343378dae844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::ExceptionPointerVirtReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the current MBB is a landing pad, the exception pointer and exception selector registers are copied into these virtual registers by SelectionDAGISel::PrepareEHLandingPad().</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### ExceptionSelectorVirtReg {#aa783b39d93936bd28d34abee51edb2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::ExceptionSelectorVirtReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### Fn {#aa6af88ef964b6f03824a35fa0081efa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function* llvm::FunctionLoweringInfo::Fn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel/#ac8e1ee94bced949e039028f65dc5784d">anonymous{ARMFastISel.cpp}::ARMFastISel::ARMFastISel</a>, <a href="#ad89b3db56d061cd3cf70ad2a94c66b8a">getValueFromVirtualReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#ae62d9e89cea91d950a28eee7e5a32088">anonymous{MipsFastISel.cpp}::MipsFastISel::MipsFastISel</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### InsertPt {#a90b6dd55afe6936ce5854c71baadbf92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::iterator llvm::FunctionLoweringInfo::InsertPt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MBB - The current insert position inside the current block.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### MBB {#a9893077f1825192ca0f3d173afefb573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::FunctionLoweringInfo::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MBB - The current block.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### MBBMap {#acb2d89ef8260d2242a6f565d997c1616}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineBasicBlock *&gt; llvm::FunctionLoweringInfo::MBBMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping from LLVM basic block number to their machine block.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>, <a href="#a14a2bf30885cc5b91b86a564759980bb">getMBB</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### MF {#ac9287d39f216ac61b351d95a4f7e3df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::FunctionLoweringInfo::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armfastisel-cpp-/armfastisel/#ac8e1ee94bced949e039028f65dc5784d">anonymous{ARMFastISel.cpp}::ARMFastISel::ARMFastISel</a>, <a href="#acada979e9424b6f61142bbca85a0fea0">ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#aa23959d9b3463aec95209a1fe73c1e3f">llvm::ARM::createFastISel</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a40e9166415077d71f840a81b21a1313a">llvm::MipsTargetLowering::createFastISel</a>, <a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a>, <a href="#ab9ae2c8bd9d78d63eede987561ba39ee">CreateRegs</a>, <a href="#aeed2af86c53eb65a738276c01feb4933">getCatchPadExceptionPointerVReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsfastisel-cpp-/mipsfastisel/#ae62d9e89cea91d950a28eee7e5a32088">anonymous{MipsFastISel.cpp}::MipsFastISel::MipsFastISel</a>, <a href="#a971f804e98558726a547fa8fefe28a11">set</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#aa2401a1ee0b3876ea3c1cdfe7cd643bf">anonymous{X86FastISel.cpp}::X86FastISel::X86FastISel</a>.</p>

</div>
</div>

### OrigNumPHINodesToUpdate {#a2b0200bc03523f2fed22a34edeb8d5d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionLoweringInfo::OrigNumPHINodesToUpdate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### PHINodesToUpdate {#a99d5184cf5e487012782adccecbc2dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;MachineInstr*, unsigned&gt; &gt; llvm::FunctionLoweringInfo::PHINodesToUpdate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PHINodesToUpdate - A list of phi instructions whose operand list will be updated after processing the current basic block.</p>


<p>TODO: This isn't per-function state, it's per-basic-block state. But there's no other convenient place for it to live right now.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### PreferredExtendType {#aed51a923085b2a92ae822375e5ca6913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, ISD::NodeType&gt; llvm::FunctionLoweringInfo::PreferredExtendType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> the preferred extend type (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">ISD::SIGN_EXTEND</a> or <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">ISD::ZERO_EXTEND</a>) for a value.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### PreprocessedDbgDeclares {#a7fa8e84e7d5f268d5bbc8bd93d497867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const DbgDeclareInst *, 8&gt; llvm::FunctionLoweringInfo::PreprocessedDbgDeclares</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of dbg.declare instructions handled after argument lowering and before ISel proper.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

### PreprocessedDVRDeclares {#a0f535e2de728fc1a44caffba9eeea9a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;const DbgVariableRecord *, 8&gt; llvm::FunctionLoweringInfo::PreprocessedDVRDeclares</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

### RegFixups {#aa749dd21cbc2b9c9dc1482bc714aac6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, Register&gt; llvm::FunctionLoweringInfo::RegFixups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RegFixups - Registers which need to be replaced after isel is done.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

### RegInfo {#adda780c93aae358f7ee00c01081ee840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::FunctionLoweringInfo::RegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#addc080407660a5304ac3b7005d242bd2">CreateReg</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### RegsWithFixups {#a1d6410ef3df4aff6a61a5dbbf252f3a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;Register&gt; llvm::FunctionLoweringInfo::RegsWithFixups</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

### SplitCSR {#a758d6756fc413f99be3028b9068c8e06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionLoweringInfo::SplitCSR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if part of the CSRs will be handled via explicit copies.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

### StatepointRelocationMaps {#a460bac4fe51e0dcd08f1fb328005926d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Instruction *, StatepointSpillMapTy&gt; llvm::FunctionLoweringInfo::StatepointRelocationMaps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a6ac2c0f0b7439c31332c78cd1ca5c4fe">findPreviousSpillSlot</a>.</p>

</div>
</div>

### StatepointStackSlots {#a9691f14813e0540e6a1c90cfdad39df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 50&gt; llvm::FunctionLoweringInfo::StatepointStackSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>StatepointStackSlots - A list of temporary stack slots (frame indices) used to spill values at a statepoint.</p>


<p>We store them here to enable reuse of the same stack slots across different statepoints in different basic blocks.</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#adec63d991d7eb048d87fa3888099c848">reservePreviousStackSlotForValue</a> and <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#aeb4b5a7ad5a49f17f8a34890eb6efefe">llvm::StatepointLoweringState::startNewStatepoint</a>.</p>

</div>
</div>

### StaticAllocaMap {#a3ec121cc6c5c5141f5ac46f101727e8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const AllocaInst*, int&gt; llvm::FunctionLoweringInfo::StaticAllocaMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>StaticAllocaMap - Keep track of frame indices for fixed sized allocas in the entry block.</p>


<p>This allows the allocas to be efficiently referenced anywhere in the function.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### TLI {#ad6fd4272e74d05a2450311a32099b5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* llvm::FunctionLoweringInfo::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#acada979e9424b6f61142bbca85a0fea0">ComputePHILiveOutRegInfo</a>, <a href="#addc080407660a5304ac3b7005d242bd2">CreateReg</a>, <a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a>, <a href="#ab9ae2c8bd9d78d63eede987561ba39ee">CreateRegs</a>, <a href="#ad89b3db56d061cd3cf70ad2a94c66b8a">getValueFromVirtualReg</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### UA {#a44d7756207368edfc6415f7f180836bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const UniformityInfo* llvm::FunctionLoweringInfo::UA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a02e2a094addb0070a73d9c9d05098246">CreateRegs</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### ValueMap {#a7fe2a1d04fbf581308aa60fa34e22069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value *, Register&gt; llvm::FunctionLoweringInfo::ValueMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a> - Since we emit code for the function a basic block at a time, we must remember which virtual registers hold the values for cross-basic-block values.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>, <a href="#acada979e9424b6f61142bbca85a0fea0">ComputePHILiveOutRegInfo</a>, <a href="#ad89b3db56d061cd3cf70ad2a94c66b8a">getValueFromVirtualReg</a>, <a href="#a6acfcd7e0cfb4ea7791d581e7f8dbd9d">InitializeRegForValue</a>, <a href="#a39bc44baeb40615967a3ce797fb27900">InvalidatePHILiveOutRegInfo</a>, <a href="#a54f8a969772167ed351abae3f26303f3">isExportedInst</a> and <a href="#a971f804e98558726a547fa8fefe28a11">set</a>.</p>

</div>
</div>

### VirtReg2Value {#adc73312d3b0c4b5a5b4b1789c72ae94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, const Value*&gt; llvm::FunctionLoweringInfo::VirtReg2Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VirtReg2Value map is needed by the Divergence Analysis driven instruction selection.</p>


<p>It is reverted <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>. It is computed in lazy style - on demand. It is used to get the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> corresponding to the live in virtual register and is called from the TargetLowerinInfo::isSDNodeSourceOfDivergence.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>, <a href="#ad89b3db56d061cd3cf70ad2a94c66b8a">getValueFromVirtualReg</a> and <a href="#a6acfcd7e0cfb4ea7791d581e7f8dbd9d">InitializeRegForValue</a>.</p>

</div>
</div>

### VisitedBBs {#a2d79b9982e5b7c8f3e2a181727a35778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool&gt; llvm::FunctionLoweringInfo::VisitedBBs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of basic blocks visited thus far by instruction selection.</p>


<p>Indexed by basic block number.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>


<p>Referenced by <a href="#a1281235664d14beac83662b9f943e6d1">clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### LiveOutRegInfo {#a9ddcd95fbba28a3d277b9514757f9d6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;LiveOutInfo, VirtReg2IndexFunctor&gt; llvm::FunctionLoweringInfo::LiveOutRegInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LiveOutRegInfo - Information about live out vregs.</p>

<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/functionloweringinfo-h">FunctionLoweringInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/functionloweringinfo-cpp">FunctionLoweringInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
