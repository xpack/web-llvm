---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/amdgpuregisterbankinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AMDGPURegisterBankInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::AMDGPURegisterBankInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">Target/AMDGPU/AMDGPURegisterBankInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/amdgpugenregisterbankinfo">AMDGPUGenRegisterBankInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides the information for the target register banks. <a href="/web-llvm/docs/api/classes/llvm/amdgpugenregisterbankinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542fc1282cd157921c7f0900b73c63dd">AMDGPURegisterBankInfo</a> (const GCNSubtarget &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2188152bd06bdcbbbc6e200395a6d0">buildVCopy</a> (MachineIRBuilder &amp;B, Register DstReg, Register SrcReg) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d33fd387b81b22c1074a78d30192fea">collectWaterfallOperands</a> (SmallSet&lt; Register, 4 &gt; &amp;SGPROperandRegs, MachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, ArrayRef&lt; unsigned &gt; OpIndices) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a> (MachineIRBuilder &amp;B, iterator_range&lt; MachineBasicBlock::iterator &gt; Range, SmallSet&lt; Register, 4 &gt; &amp;SGPROperandRegs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Legalize instruction <span class="doxyComputerOutput">MI</span> where operands in <span class="doxyComputerOutput">OpIndices</span> must be SGPRs. <a href="#a533cd1035e03cdca3da433e98e77e430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af693d8401a06eab53b8b5b2d6df05243">buildReadFirstLane</a> (MachineIRBuilder &amp;B, MachineRegisterInfo &amp;MRI, Register Src) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a119490671008a43096dc815e2f586">executeInWaterfallLoop</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, ArrayRef&lt; unsigned &gt; OpIndices) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9640a886bae2966a9b445fc869935f">constrainOpWithReadfirstlane</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, unsigned OpIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0494e300dac616c8ca39b2dbc8b1276c">applyMappingDynStackAlloc</a> (MachineIRBuilder &amp;B, const OperandsMapper &amp;OpdMapper, MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ac3f636dddf683cf1f9b7f1a60b1ae">applyMappingLoad</a> (MachineIRBuilder &amp;B, const OperandsMapper &amp;OpdMapper, MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6db02afb81ab497196f6c979f040c063">applyMappingImage</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, const OperandsMapper &amp;OpdMapper, int RSrcIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8532a373e31385aa7f7ff3c4d14eff4b">setBufferOffsets</a> (MachineIRBuilder &amp;B, Register CombinedOffset, Register &amp;VOffsetReg, Register &amp;SOffsetReg, int64_t &amp;InstOffsetVal, Align Alignment) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb1a8a9ef7b460687963fb7968fb7626">applyMappingSBufferLoad</a> (MachineIRBuilder &amp;B, const OperandsMapper &amp;OpdMapper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67457fbc2d167a5a1a18124bd446278f">applyMappingBFE</a> (MachineIRBuilder &amp;B, const OperandsMapper &amp;OpdMapper, bool Signed) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ce3aa458b07483cb7422b0303b589b">applyMappingMAD_64_32</a> (MachineIRBuilder &amp;B, const OperandsMapper &amp;OpdMapper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd96526160e781989c15d6879ad1f9f1">applyMappingSMULU64</a> (MachineIRBuilder &amp;B, const OperandsMapper &amp;OpdMapper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5e4d60d30f6101d9aedbc3e0e13bc0">handleD16VData</a> (MachineIRBuilder &amp;B, MachineRegisterInfo &amp;MRI, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle register layout difference for f16 images for some subtargets. <a href="#a5f5e4d60d30f6101d9aedbc3e0e13bc0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0924254734e306adcc8cdcd0e2a3544c">splitBufferOffsets</a> (MachineIRBuilder &amp;B, Register Offset) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a> (MachineIRBuilder &amp;Builder, const OperandsMapper &amp;OpdMapper) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a0c85003f2e4060a7b61ebff7c2fb33cd">RegisterBankInfo::applyMapping</a>. <a href="#a66655fdd73a951d10ad6fb804f0fac98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941f1e23c69340ff634ea8bbb015e6d0">getValueMappingForPtr</a> (const MachineRegisterInfo &amp;MRI, Register Ptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the mapping for a pointer argument. <a href="#a941f1e23c69340ff634ea8bbb015e6d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">RegisterBankInfo::InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61f99fec329ba9cbb633996ee0452363">getInstrMappingForLoad</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bc45f557d3d69066e2c03a39ca51793">getRegBankID</a> (Register Reg, const MachineRegisterInfo &amp;MRI, unsigned Default=AMDGPU::VGPRRegBankID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854d61301ea33c4f27021c50ae9e8bdf">getSGPROpMapping</a> (Register Reg, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dca2bae7706ebd6d1d1681137040243">getVGPROpMapping</a> (Register Reg, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acefa289ec10ccb3fb0a928a8609b3724">getAGPROpMapping</a> (Register Reg, const MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a909ca36ce602ebf9224694d163064009">split64BitValueForMapping</a> (MachineIRBuilder &amp;B, SmallVector&lt; Register, 2 &gt; &amp;Regs, LLT HalfTy, Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split 64-bit value <span class="doxyComputerOutput">Reg</span> into two 32-bit halves and populate them into <span class="doxyComputerOutput">Regs</span>. <a href="#a909ca36ce602ebf9224694d163064009">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned NumOps&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">InstructionMappings</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a317794ba2e8cf8f07ca39ade5115d66a">addMappingFromTable</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const std::array&lt; unsigned, NumOps &gt; RegSrcOpIdx, ArrayRef&lt; OpRegBankEntry&lt; NumOps &gt; &gt; Table) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">RegisterBankInfo::InstructionMappings</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d554817cae8090009510677635a1c7b">getInstrAlternativeMappingsIntrinsic</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">RegisterBankInfo::InstructionMappings</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d8badc0c5eeec688355e80d3f116ac3">getInstrAlternativeMappingsIntrinsicWSideEffects</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9561c2ca7dd4fcd8cf869156fbc79d79">getMappingType</a> (const MachineRegisterInfo &amp;MRI, const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a764fec0343cb91d369059651a11e4">isSALUMapping</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba8269780a1b283db0509e18d3f99d92">getDefaultMappingSOP</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a779141ce10443d7b7d15b7ca76160">getDefaultMappingVOP</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb1babbd49300ea60d3fe16eb5472749">getDefaultMappingAllVGPR</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d74d69cbd37e794e77ff37aa8d3401">getImageMapping</a> (const MachineRegisterInfo &amp;MRI, const MachineInstr &amp;MI, int RsrcIdx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e00e65ed27b4878c544a984ae22329b">isDivergentRegBank</a> (const RegisterBank *RB) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the register bank is considered divergent. <a href="#a9e00e65ed27b4878c544a984ae22329b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36730804c60ca1d41a6a15d014d67656">copyCost</a> (const RegisterBank &amp;A, const RegisterBank &amp;B, TypeSize Size) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cost of a copy from <span class="doxyComputerOutput">B</span> to <span class="doxyComputerOutput">A</span>, or put differently, get the cost of A = COPY B. <a href="#a36730804c60ca1d41a6a15d014d67656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac390939d904c03a62f806bac6ae2626c">getBreakDownCost</a> (const ValueMapping &amp;ValMapping, const RegisterBank *CurBank=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the cost of using <span class="doxyComputerOutput">ValMapping</span> to decompose a register. <a href="#ac390939d904c03a62f806bac6ae2626c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53fe77055b01a82e1a53e7798cef110a">getRegBankFromRegClass</a> (const TargetRegisterClass &amp;RC, LLT) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a register bank that covers <span class="doxyComputerOutput">RC</span>. <a href="#a53fe77055b01a82e1a53e7798cef110a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ebf01237ea354d0baf26fae2f0a04a3">isScalarLoadLegal</a> (const MachineInstr &amp;MI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">InstructionMappings</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab65adad01ce4004d6fe95c5b740190ab">getInstrAlternativeMappings</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alternative mappings for <span class="doxyComputerOutput">MI</span>. <a href="#ab65adad01ce4004d6fe95c5b740190ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping">InstructionMapping</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a> (const MachineInstr &amp;MI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function must return a legal mapping, because <a href="#ab65adad01ce4004d6fe95c5b740190ab">AMDGPURegisterBankInfo::getInstrAlternativeMappings()</a> is not called in <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">RegBankSelect::Mode::Fast</a>. <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned NumOps&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ac89dbbb6460391f27fb352c20c600769">RegisterBankInfo::InstructionMappings</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7af7bb833a1702eacc1b0974ee514698">addMappingFromTable</a> (const MachineInstr &amp;MI, const MachineRegisterInfo &amp;MRI, const std::array&lt; unsigned, NumOps &gt; RegSrcOpIdx, ArrayRef&lt; OpRegBankEntry&lt; NumOps &gt; &gt; Table) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf7ba583177fe2201a44a53683d7a0b4">foldExtractEltToCmpSelect</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, const OperandsMapper &amp;OpdMapper) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0038eb65ffac06415fc2d58e1ed3a4">foldInsertEltToCmpSelect</a> (MachineIRBuilder &amp;B, MachineInstr &amp;MI, const OperandsMapper &amp;OpdMapper) const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774f70ec47e4b324901ebbb23573157d">TII</a></td>
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


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AMDGPURegisterBankInfo() {#a542fc1282cd157921c7f0900b73c63dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPURegisterBankInfo::AMDGPURegisterBankInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget">GCNSubtarget</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>, <a href="#a774f70ec47e4b324901ebbb23573157d">TII</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addMappingFromTable() {#a317794ba2e8cf8f07ca39ade5115d66a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned NumOps&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionMappings llvm::AMDGPURegisterBankInfo::addMappingFromTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; unsigned, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">NumOps</a> &gt; RegSrcOpIdx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/amdgpuregisterbankinfo/opregbankentry">OpRegBankEntry</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">NumOps</a> &gt; &gt; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#ab65adad01ce4004d6fe95c5b740190ab">getInstrAlternativeMappings</a>, <a href="#a9d554817cae8090009510677635a1c7b">getInstrAlternativeMappingsIntrinsic</a> and <a href="#a3d8badc0c5eeec688355e80d3f116ac3">getInstrAlternativeMappingsIntrinsicWSideEffects</a>.</p>

</div>
</div>

### addMappingFromTable() {#a7af7bb833a1702eacc1b0974ee514698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned NumOps&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterBankInfo::InstructionMappings llvm::AMDGPURegisterBankInfo::addMappingFromTable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::array&lt; unsigned, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">NumOps</a> &gt; RegSrcOpIdx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/amdgpuregisterbankinfo/opregbankentry">OpRegBankEntry</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">NumOps</a> &gt; &gt; Table)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7efe71b047699bd4139c3e5f36318aa2">llvm::RegisterBankInfo::Sizes</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>

</div>
</div>

### applyMappingBFE() {#a67457fbc2d167a5a1a18124bd446278f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::applyMappingBFE (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper, bool Signed)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a08b29851bd7d2ce50c53e87b9043532a">llvm::RegisterBankInfo::OperandsMapper::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a397c999d8b2ead3f13eba866dfc3295e">llvm::RegisterBankInfo::OperandsMapper::getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a841196bdb378891dcedb1c23a02a30d2">llvm::RegisterBankInfo::OperandsMapper::getMRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="#a774f70ec47e4b324901ebbb23573157d">TII</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### applyMappingDynStackAlloc() {#a0494e300dac616c8ca39b2dbc8b1276c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::applyMappingDynStackAlloc (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4b2e7a84faf3d7b6ffb84b541358e00">llvm::assumeAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#a453c74e2daac0745b53f8b31c11fc50ca5a5dea77f2a0aaffed9741ae04e8d865">llvm::TargetFrameLowering::StackGrowsUp</a>, <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a> and <a href="/web-llvm/docs/api/structs/llvm/align/#a80735739b49cf97a491922c8f9af2cc1">llvm::Align::value</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### applyMappingImage() {#a6db02afb81ab497196f6c979f040c063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::applyMappingImage (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper, int RSrcIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### applyMappingImpl() {#a66655fdd73a951d10ad6fb804f0fac98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPURegisterBankInfo::applyMappingImpl (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
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

<p>See <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a0c85003f2e4060a7b61ebff7c2fb33cd">RegisterBankInfo::applyMapping</a>.</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 2205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="#a67457fbc2d167a5a1a18124bd446278f">applyMappingBFE</a>, <a href="#a0494e300dac616c8ca39b2dbc8b1276c">applyMappingDynStackAlloc</a>, <a href="#a6db02afb81ab497196f6c979f040c063">applyMappingImage</a>, <a href="#a87ac3f636dddf683cf1f9b7f1a60b1ae">applyMappingLoad</a>, <a href="#a59ce3aa458b07483cb7422b0303b589b">applyMappingMAD_64_32</a>, <a href="#afb1a8a9ef7b460687963fb7968fb7626">applyMappingSBufferLoad</a>, <a href="#afd96526160e781989c15d6879ad1f9f1">applyMappingSMULU64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrspan/#a80cf68c228dc30772af16e45ec4f825c">llvm::MachineInstrSpan::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="#a4a2188152bd06bdcbbbc6e200395a6d0">buildVCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#a1d33fd387b81b22c1074a78d30192fea">collectWaterfallOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="#aae9640a886bae2966a9b445fc869935f">constrainOpWithReadfirstlane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrspan/#ad7baac24bfd68006d3efe73d6c3037f4">llvm::MachineInstrSpan::end</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a6448cfc677ca653b92b0c0bf5f3b29cd">extendLow32IntoHigh32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afc1af790923d299c9f6c0b631034dbc6">llvm::AMDGPU::getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a79ebc5d429e92dbe3e0c6009ec8e55b4">getExtendOp</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a7f0521fa2de44271fd4b909ea7351ef3">llvm::MachineBasicBlock::getFirstTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#afa3232adbead0d5386a1e7636a9d772f">getHalfSizedType</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a08b29851bd7d2ce50c53e87b9043532a">llvm::RegisterBankInfo::OperandsMapper::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a30dd396c5b40cd86c1591872e574ccdf">llvm::Type::getInt32Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae37ecdb91b779cb417f2320ef5592dcd">llvm::AMDGPU::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a397c999d8b2ead3f13eba866dfc3295e">llvm::RegisterBankInfo::OperandsMapper::getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a841196bdb378891dcedb1c23a02a30d2">llvm::RegisterBankInfo::OperandsMapper::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acf6442108e21e7e5379feb8962de65b7">llvm::MachineBasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="#a5bc45f557d3d69066e2c03a39ca51793">getRegBankID</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#af23faa9ae580c4a451da006e3567b297">llvm::RegisterBankInfo::OperandsMapper::getVRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22dc5c679c09756d04fe07f9e22baf84">llvm::AMDGPU::isFlatGlobalAddrSpace</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/rsrcintrinsic/#ad7b8f270ab4300ebf1befec5932ce66f">llvm::AMDGPU::RsrcIntrinsic::IsImage</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">llvm::LegalizerHelper::Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af678c3209f593c182c0043fd0fce81fe">llvm::AMDGPU::lookupRsrcIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a34f7e7a55fa5743fadeef838b7c9ece9">llvm::LegalizerHelper::lowerAbsToMaxNeg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#aeae677889401c02a8def9a0508e858c7">reinsertVectorIndexAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/rsrcintrinsic/#a10176381ae19f290f96e88b90da7e0de">llvm::AMDGPU::RsrcIntrinsic::RsrcArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a2b96ee4926f7c19420d19ecaf7adc1a8">S64</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#abd86d813757b6a6e4b94c03a856002a4">setRegsToType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a909ca36ce602ebf9224694d163064009">split64BitValueForMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>, <a href="#a774f70ec47e4b324901ebbb23573157d">TII</a>, <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a5227e311d2ae980540efa4033943595e">unpackV2S16ToS32</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aacc36b9bbb74a3cdb987aa8f28b269e3">llvm::LegalizerHelper::widenScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### applyMappingLoad() {#a87ac3f636dddf683cf1f9b7f1a60b1ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::applyMappingLoad (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1af3a547aa91b97183a165b876de8e24d8">llvm::AMDGPUAS::BUFFER_RESOURCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#af11a4c235044d52af7fbf840dec3f278">llvm::LLT::divide</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aa8fe481cda91a90b364e410009785003">llvm::LegalizerHelper::fewerElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3f583e2bb417139560bde043214d064a">llvm::MachineMemOperand::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abc15369ab4cc583332950b913e2ef1dd">llvm::MachineMemOperand::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a08b29851bd7d2ce50c53e87b9043532a">llvm::RegisterBankInfo::OperandsMapper::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#af23faa9ae580c4a451da006e3567b297">llvm::RegisterBankInfo::OperandsMapper::getVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusubtarget/#a53c0ee4138bfbf9e0410a65e0eaa36e2a41fdc37fae4d310162da1fea46a8aca8">llvm::AMDGPUSubtarget::GFX12</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad67d696d7847623b61c63942d86f27ef">llvm::AMDGPU::isExtendedGlobalAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a3989251b1a714fc8296685f77eac6e87">llvm::LLT::isScalar</a>, <a href="#a7ebf01237ea354d0baf26fae2f0a04a3">isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">llvm::LegalizerHelper::Legalized</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#ab4c2bc39e4119d3c2098986cfd7be179">splitUnequalType</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#af1deb020986939504194841306a9da79">widen96To128</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### applyMappingMAD\_64\_32() {#a59ce3aa458b07483cb7422b0303b589b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::applyMappingMAD_64_32 (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1582 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#af693d8401a06eab53b8b5b2d6df05243">buildReadFirstLane</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a397c999d8b2ead3f13eba866dfc3295e">llvm::RegisterBankInfo::OperandsMapper::getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a841196bdb378891dcedb1c23a02a30d2">llvm::RegisterBankInfo::OperandsMapper::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a54d7212b9b2c57cced42037ae2fa7c61">llvm::PatternMatch::m_ZeroInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### applyMappingSBufferLoad() {#afb1a8a9ef7b460687963fb7968fb7626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::applyMappingSBufferLoad (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1358 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrspan/#a80cf68c228dc30772af16e45ec4f825c">llvm::MachineInstrSpan::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrspan/#ad7baac24bfd68006d3efe73d6c3037f4">llvm::MachineInstrSpan::end</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a08b29851bd7d2ce50c53e87b9043532a">llvm::RegisterBankInfo::OperandsMapper::getInstrMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a397c999d8b2ead3f13eba866dfc3295e">llvm::RegisterBankInfo::OperandsMapper::getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a841196bdb378891dcedb1c23a02a30d2">llvm::RegisterBankInfo::OperandsMapper::getMRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#afa990eb71e5b4aae561ac8c002da2b44">getSBufferLoadCorrespondingBufferLoadOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7b999a936bc7a4d45dfadbe356e77b3f">llvm::MachineMemOperand::MODereferenceable</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac63dd9c4fe69bfeaac7a363fda846ac6">llvm::MachineMemOperand::MOInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#a8532a373e31385aa7f7ff3c4d14eff4b">setBufferOffsets</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### applyMappingSMULU64() {#afd96526160e781989c15d6879ad1f9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPURegisterBankInfo::applyMappingSMULU64 (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5c8b942e0a2e8ebef5a138c8d3c4462c">llvm::RegisterBankInfo::applyDefaultMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a397c999d8b2ead3f13eba866dfc3295e">llvm::RegisterBankInfo::OperandsMapper::getMI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#a841196bdb378891dcedb1c23a02a30d2">llvm::RegisterBankInfo::OperandsMapper::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#af23faa9ae580c4a451da006e3567b297">llvm::RegisterBankInfo::OperandsMapper::getVRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#abd86d813757b6a6e4b94c03a856002a4">setRegsToType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a909ca36ce602ebf9224694d163064009">split64BitValueForMapping</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### buildReadFirstLane() {#af693d8401a06eab53b8b5b2d6df05243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AMDGPURegisterBankInfo::buildReadFirstLane (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a1cfd8b1df608cb89b0acb94d29d447b3">llvm::RegisterBankInfo::constrainGenericRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a59ce3aa458b07483cb7422b0303b589b">applyMappingMAD_64_32</a>, <a href="#aae9640a886bae2966a9b445fc869935f">constrainOpWithReadfirstlane</a> and <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>.</p>

</div>
</div>

### buildVCopy() {#a4a2188152bd06bdcbbbc6e200395a6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::buildVCopy (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SrcReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1870 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a1cfd8b1df608cb89b0acb94d29d447b3">llvm::RegisterBankInfo::constrainGenericRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### collectWaterfallOperands() {#a1d33fd387b81b22c1074a78d30192fea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::collectWaterfallOperands (<a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt; &amp; SGPROperandRegs, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; OpIndices)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a34384400167eb6ebf71fa89d98ba03bc">llvm::SmallSet&lt; T, N, C &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a> and <a href="#ab9a119490671008a43096dc815e2f586">executeInWaterfallLoop</a>.</p>

</div>
</div>

### constrainOpWithReadfirstlane() {#aae9640a886bae2966a9b445fc869935f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPURegisterBankInfo::constrainOpWithReadfirstlane (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#af693d8401a06eab53b8b5b2d6df05243">buildReadFirstLane</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>.</p>

</div>
</div>

### copyCost() {#a36730804c60ca1d41a6a15d014d67656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPURegisterBankInfo::copyCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/typesize">TypeSize</a> Size)</td>
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

<p>Get the cost of a copy from <span class="doxyComputerOutput">B</span> to <span class="doxyComputerOutput">A</span>, or put differently, get the cost of A = COPY B.</p>


<p>Since register banks may cover different size, <span class="doxyComputerOutput">Size</span> specifies what will be the size in bits that will be copied around.</p>



:::info
<p>Since this is a copy, both registers have the same size.</p>
:::


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ace62a3b4e043e1740264ffd8a6b6cfb5">llvm::RegisterBankInfo::copyCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a8c6b6408d508158782ddfaf264a20641">isVectorRegisterBank</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### executeInWaterfallLoop() {#a533cd1035e03cdca3da433e98e77e430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::executeInWaterfallLoop (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &gt; Range, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt; &amp; SGPROperandRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Legalize instruction <span class="doxyComputerOutput">MI</span> where operands in <span class="doxyComputerOutput">OpIndices</span> must be SGPRs.</p>


<p>If any of the required SGPR operands are VGPRs, perform a waterfall loop to execute the instruction for each unique combination of values in all lanes in the wave. The block will be split such that rest of the instructions are moved to a new block.</p>


<p>Essentially performs this loop: Save Execution Mask For (Lane : Wavefront) { Enable Lane, Disable all other lanes SGPR = read SGPR value for current lane from VGPR VGPRResult[Lane] = use_op SGPR } Restore Execution Mask</p>


<p>There is additional complexity to try for compare values to identify the unique values used.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 775 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="#af693d8401a06eab53b8b5b2d6df05243">buildReadFirstLane</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a9ddde91ef09476d28a088fe57f8e2921">llvm::RegState::Kill</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>, <a href="#a774f70ec47e4b324901ebbb23573157d">TII</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a6db02afb81ab497196f6c979f040c063">applyMappingImage</a>, <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>, <a href="#afb1a8a9ef7b460687963fb7968fb7626">applyMappingSBufferLoad</a> and <a href="#ab9a119490671008a43096dc815e2f586">executeInWaterfallLoop</a>.</p>

</div>
</div>

### executeInWaterfallLoop() {#ab9a119490671008a43096dc815e2f586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::executeInWaterfallLoop (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; OpIndices)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1d33fd387b81b22c1074a78d30192fea">collectWaterfallOperands</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getAGPROpMapping() {#acefa289ec10ccb3fb0a928a8609b3724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * AMDGPURegisterBankInfo::getAGPROpMapping (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3756 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getBreakDownCost() {#ac390939d904c03a62f806bac6ae2626c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPURegisterBankInfo::getBreakDownCost (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping">ValueMapping</a> &amp; ValMapping, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> * CurBank=nullptr)</td>
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

<p>Get the cost of using <span class="doxyComputerOutput">ValMapping</span> to decompose a register.</p>


<p>This is similar to <a href="#a36730804c60ca1d41a6a15d014d67656">copyCost</a>, except for cases where multiple copy-like operations need to be inserted. If the register is used as a source operand and already has a bank assigned, <span class="doxyComputerOutput">CurBank</span> is non-null.</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#ae3003e8b89a759af674cb22ed2b67d2e">llvm::RegisterBankInfo::ValueMapping::BreakDown</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#afac28dfebeb6f31c2c87dd1acdcd038f">llvm::RegisterBankInfo::PartialMapping::Length</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#a83b9746150eb1c8820d65bca34b8d950">llvm::RegisterBankInfo::ValueMapping::NumBreakDowns</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ae78f517f813c1983db970736287379e1">llvm::RegisterBankInfo::PartialMapping::RegBank</a> and <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#a0c55804243f2f158a9afa64f0f764c35">llvm::RegisterBankInfo::PartialMapping::StartIdx</a>.</p>

</div>
</div>

### getDefaultMappingAllVGPR() {#abb1babbd49300ea60d3fe16eb5472749}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AMDGPURegisterBankInfo::getDefaultMappingAllVGPR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getDefaultMappingSOP() {#aba8269780a1b283db0509e18d3f99d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AMDGPURegisterBankInfo::getDefaultMappingSOP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/srcop/#ae229785d0c8a8ce25d34be18fe150a54">llvm::SrcOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getDefaultMappingVOP() {#ae6a779141ce10443d7b7d15b7ca76160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AMDGPURegisterBankInfo::getDefaultMappingVOP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3580 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getImageMapping() {#a27d74d69cbd37e794e77ff37aa8d3401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AMDGPURegisterBankInfo::getImageMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, int RsrcIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="#a5bc45f557d3d69066e2c03a39ca51793">getRegBankID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getInstrAlternativeMappings() {#ab65adad01ce4004d6fe95c5b740190ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterBankInfo::InstructionMappings AMDGPURegisterBankInfo::getInstrAlternativeMappings (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Get the alternative mappings for <span class="doxyComputerOutput">MI</span>.</p>


<p>Alternative in the sense different from getInstrMapping.</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a317794ba2e8cf8f07ca39ade5115d66a">addMappingFromTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ac33fa4c8cfeb9287f51f95404a459de8">llvm::LLT::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a104c33de0485a9518a9cae99b7023c84">llvm::RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="#a9d554817cae8090009510677635a1c7b">getInstrAlternativeMappingsIntrinsic</a>, <a href="#a3d8badc0c5eeec688355e80d3f116ac3">getInstrAlternativeMappingsIntrinsicWSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="#a7ebf01237ea354d0baf26fae2f0a04a3">isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a77b1c964e2ff99057bf5e75140457abe">llvm::AMDGPUAS::LOCAL_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aec164f45437d8827346f2d8ec645479a">llvm::AMDGPUAS::PRIVATE_ADDRESS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a5b71ba6fa435ec288aba849e113721a7">llvm::AMDGPUAS::REGION_ADDRESS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>

</div>
</div>

### getInstrAlternativeMappingsIntrinsic() {#a9d554817cae8090009510677635a1c7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterBankInfo::InstructionMappings AMDGPURegisterBankInfo::getInstrAlternativeMappingsIntrinsic (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a317794ba2e8cf8f07ca39ade5115d66a">addMappingFromTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a104c33de0485a9518a9cae99b7023c84">llvm::RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#ab65adad01ce4004d6fe95c5b740190ab">getInstrAlternativeMappings</a>.</p>

</div>
</div>

### getInstrAlternativeMappingsIntrinsicWSideEffects() {#a3d8badc0c5eeec688355e80d3f116ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RegisterBankInfo::InstructionMappings AMDGPURegisterBankInfo::getInstrAlternativeMappingsIntrinsicWSideEffects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a317794ba2e8cf8f07ca39ade5115d66a">addMappingFromTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a104c33de0485a9518a9cae99b7023c84">llvm::RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="#ab65adad01ce4004d6fe95c5b740190ab">getInstrAlternativeMappings</a>.</p>

</div>
</div>

### getInstrMapping() {#abb21f77ed3dc15eb330b93b3efaa94ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AMDGPURegisterBankInfo::getInstrMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>This function must return a legal mapping, because <a href="#ab65adad01ce4004d6fe95c5b740190ab">AMDGPURegisterBankInfo::getInstrAlternativeMappings()</a> is not called in <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a033277264e702883c8bbf13871247a84a764570eb91457744372935b426a1a397">RegBankSelect::Mode::Fast</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> mapping that would cause a VGPR to SGPR generated is illegal.</p>


<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3773 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a803fef00c0213ef55fae6339086d86b1">llvm::RegisterBankInfo::cannotCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="#acefa289ec10ccb3fb0a928a8609b3724">getAGPROpMapping</a>, <a href="#abb1babbd49300ea60d3fe16eb5472749">getDefaultMappingAllVGPR</a>, <a href="#aba8269780a1b283db0509e18d3f99d92">getDefaultMappingSOP</a>, <a href="#ae6a779141ce10443d7b7d15b7ca76160">getDefaultMappingVOP</a>, <a href="/web-llvm/docs/api/classes/llvm/typesize/#a003b4369b4130e669dc9139798e0193c">llvm::TypeSize::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="#a27d74d69cbd37e794e77ff37aa8d3401">getImageMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="#a61f99fec329ba9cbb633996ee0452363">getInstrMappingForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#af5535a05921d5db8486cc4ce527b066f">llvm::RegisterBankInfo::getInstrMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a62766c75f88612ffa652342472e755f6">getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae37ecdb91b779cb417f2320ef5592dcd">llvm::AMDGPU::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a640c554d91abd68270b79cdef71b99a2">llvm::RegisterBankInfo::getInvalidInstructionMapping</a>, <a href="#a9561c2ca7dd4fcd8cf869156fbc79d79">getMappingType</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="#a5bc45f557d3d69066e2c03a39ca51793">getRegBankID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="#a854d61301ea33c4f27021c50ae9e8bdf">getSGPROpMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5f683dcd4b6530d6f1b29d50b92e2907">llvm::RegisterBankInfo::getValueMapping</a>, <a href="#a941f1e23c69340ff634ea8bbb015e6d0">getValueMappingForPtr</a>, <a href="#a6dca2bae7706ebd6d1d1681137040243">getVGPROpMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/rsrcintrinsic/#ad7b8f270ab4300ebf1befec5932ce66f">llvm::AMDGPU::RsrcIntrinsic::IsImage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsinstprinter-cpp/#a85e8dc708ae90b1129b892cb8ae1500f">isReg</a>, <a href="#af5a764fec0343cb91d369059651a11e4">isSALUMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#af484a43d5e4fa2ff1f1790d06f2ca94d">llvm::RegisterBankInfo::InstructionMapping::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af678c3209f593c182c0043fd0fce81fe">llvm::AMDGPU::lookupRsrcIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#ae87bd5f0f34adb49edb50ea8c1351f53">llvm::SIMachineFunctionInfo::mayNeedAGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a1130bcafa3946d26a8db4ed3e3ff454c">regBankBoolUnion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a9cf2c2b46650c2af4ba811f1b08156e7">regBankUnion</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpu/rsrcintrinsic/#a10176381ae19f290f96e88b90da7e0de">llvm::AMDGPU::RsrcIntrinsic::RsrcArg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>

</div>
</div>

### getInstrMappingForLoad() {#a61f99fec329ba9cbb633996ee0452363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::InstructionMapping &amp; AMDGPURegisterBankInfo::getInstrMappingForLoad (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#ac33fa4c8cfeb9287f51f95404a459de8">llvm::LLT::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a5b7e84a2ea3cdb118f44543cdb33f670">llvm::RegisterBankInfo::getInstructionMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#ab899ee374f95aa9e56c35eae354f8188">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22dc5c679c09756d04fe07f9e22baf84">llvm::AMDGPU::isFlatGlobalAddrSpace</a>, <a href="#a7ebf01237ea354d0baf26fae2f0a04a3">isScalarLoadLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getMappingType() {#a9561c2ca7dd4fcd8cf869156fbc79d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPURegisterBankInfo::getMappingType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a9cf2c2b46650c2af4ba811f1b08156e7">regBankUnion</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getRegBankFromRegClass() {#a53fe77055b01a82e1a53e7798cef110a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBank &amp; AMDGPURegisterBankInfo::getRegBankFromRegClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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

<p>Get a register bank that covers <span class="doxyComputerOutput">RC</span>.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><span class="doxyComputerOutput">RC</span> is a user-defined register class (as opposed as one generated by <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>).</p></dd>
</dl>



:::info
<p>The mapping RC -&gt; RegBank could be built while adding the coverage for the register banks. However, we do not do it, because, at least for now, we only need this information for register classes that are used in the description of instruction. In other words, there are just a handful of them and we do not want to waste space.</p>
:::


<div class="doxyXrefSect">
<dl class="doxyXrefSectList">
<dt class="doxyXrefSectTitle"><a href=/web-llvm/docs/api/pages/todo/#_todo000003>Todo</a></dt>
<dd class="doxyXrefSectDescription">
<p>This should be <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a>'ed.</p>
</dd>
</dl>
</div>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>

</div>
</div>

### getRegBankID() {#a5bc45f557d3d69066e2c03a39ca51793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPURegisterBankInfo::getRegBankID (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, unsigned Default=AMDGPU::VGPRRegBankID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3729 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>, <a href="#a27d74d69cbd37e794e77ff37aa8d3401">getImageMapping</a>, <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a> and <a href="#a854d61301ea33c4f27021c50ae9e8bdf">getSGPROpMapping</a>.</p>

</div>
</div>

### getSGPROpMapping() {#a854d61301ea33c4f27021c50ae9e8bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * AMDGPURegisterBankInfo::getSGPROpMapping (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3737 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="#a5bc45f557d3d69066e2c03a39ca51793">getRegBankID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getValueMappingForPtr() {#a941f1e23c69340ff634ea8bbb015e6d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * AMDGPURegisterBankInfo::getValueMappingForPtr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the mapping for a pointer argument.</p>

<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3667 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#ac33fa4c8cfeb9287f51f95404a459de8">llvm::LLT::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#abea60948498472cef86d66586ded919e">llvm::RegisterBank::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a22dc5c679c09756d04fe07f9e22baf84">llvm::AMDGPU::isFlatGlobalAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### getVGPROpMapping() {#a6dca2bae7706ebd6d1d1681137040243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RegisterBankInfo::ValueMapping * AMDGPURegisterBankInfo::getVGPROpMapping (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3748 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9986db3729defa2e0181a6f8be03615e">llvm::RegisterBankInfo::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### handleD16VData() {#a5f5e4d60d30f6101d9aedbc3e0e13bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register AMDGPURegisterBankInfo::handleD16VData (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle register layout difference for f16 images for some subtargets.</p>

<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1785 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#acd57bd926bf1c8815e21e1291a54d151">S16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>.</p>

</div>
</div>

### isDivergentRegBank() {#a9e00e65ed27b4878c544a984ae22329b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::isDivergentRegBank (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbank">RegisterBank</a> * RB)</td>
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

<p>Returns true if the register bank is considered divergent.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>

</div>
</div>

### isSALUMapping() {#af5a764fec0343cb91d369059651a11e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::isSALUMapping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 3546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>.</p>

</div>
</div>

### isScalarLoadLegal() {#a7ebf01237ea354d0baf26fae2f0a04a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::isScalarLoadLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1aa6d3112da64eecbdbb50aacb5f8251e8">llvm::AMDGPUAS::CONSTANT_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpuas/#a899ad5bfccfc22965a6714929a3dfae1a1caf1e287a5fe7250388d66ed72aa0c1">llvm::AMDGPUAS::CONSTANT_ADDRESS_32BIT</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3f583e2bb417139560bde043214d064a">llvm::MachineMemOperand::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abc15369ab4cc583332950b913e2ef1dd">llvm::MachineMemOperand::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#ab991bb1444579648a165d1b134a0854d">llvm::MachineMemOperand::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a6829ff090c767b553f2390e0785adf4a">llvm::MachineMemOperand::isAtomic</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a88b252120eea5192e81cf30e81eccbe9">llvm::MachineMemOperand::isInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstrinfo/#aa510d94632f7a11fd571d2c2271fb2b5">llvm::AMDGPUInstrInfo::isUniformMMO</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a1d07cda64e7150bb7f330057c41a2965">llvm::MachineMemOperand::isVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a615f4542f26ca7383f06e780996f8ef3">llvm::MONoClobber</a> and <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>.</p>


<p>Referenced by <a href="#a87ac3f636dddf683cf1f9b7f1a60b1ae">applyMappingLoad</a>, <a href="#ab65adad01ce4004d6fe95c5b740190ab">getInstrAlternativeMappings</a> and <a href="#a61f99fec329ba9cbb633996ee0452363">getInstrMappingForLoad</a>.</p>

</div>
</div>

### setBufferOffsets() {#a8532a373e31385aa7f7ff3c4d14eff4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AMDGPURegisterBankInfo::setBufferOffsets (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> CombinedOffset, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; VOffsetReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; SOffsetReg, int64_t &amp; InstOffsetVal, <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Alignment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#afc1af790923d299c9f6c0b631034dbc6">llvm::AMDGPU::getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56f5d55460d7e31fc6c3318882f36ac7">llvm::getIConstantVRegSExtVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0edf31d256ecb3ac003bf2d81a576c9e">llvm::getOpcodeDef</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb39eef3d8e7cf19a9145c51a5e46253">llvm::getSrcRegIgnoringCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="#a774f70ec47e4b324901ebbb23573157d">TII</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#afb1a8a9ef7b460687963fb7968fb7626">applyMappingSBufferLoad</a>.</p>

</div>
</div>

### split64BitValueForMapping() {#a909ca36ce602ebf9224694d163064009}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AMDGPURegisterBankInfo::split64BitValueForMapping (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 2 &gt; &amp; Regs, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> HalfTy, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split 64-bit value <span class="doxyComputerOutput">Reg</span> into two 32-bit halves and populate them into <span class="doxyComputerOutput">Regs</span>.</p>


<p>This appropriately sets the regbank of the new registers.</p>


<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#afef42b99585e128b23a4980bc0bc1824">TRI</a>.</p>


<p>Referenced by <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a> and <a href="#afd96526160e781989c15d6879ad1f9f1">applyMappingSMULU64</a>.</p>

</div>
</div>

### splitBufferOffsets() {#a0924254734e306adcc8cdcd0e2a3544c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; Register, unsigned &gt; AMDGPURegisterBankInfo::splitBufferOffsets (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1825 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a51e652265b0217f8fdba9f95129c0d47">getBaseWithConstantOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a1fa48fff435124100b9bc18b162bcfd3">llvm::SIInstrInfo::getMaxMUBUFImmOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a33c95d7d51d4b0b421aaf3d40796b859">S32</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="#ada542413c7089fe35272a9ec47c19116">Subtarget</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### foldExtractEltToCmpSelect() {#aaf7ba583177fe2201a44a53683d7a0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::foldExtractEltToCmpSelect (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 1950 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>

</div>
</div>

### foldInsertEltToCmpSelect() {#a9d0038eb65ffac06415fc2d58e1ed3a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AMDGPURegisterBankInfo::foldInsertEltToCmpSelect (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper">OperandsMapper</a> &amp; OpdMapper)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>, definition at line 2048 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Subtarget {#ada542413c7089fe35272a9ec47c19116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GCNSubtarget&amp; llvm::AMDGPURegisterBankInfo::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="#a542fc1282cd157921c7f0900b73c63dd">AMDGPURegisterBankInfo</a>, <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>, <a href="#a87ac3f636dddf683cf1f9b7f1a60b1ae">applyMappingLoad</a>, <a href="#a59ce3aa458b07483cb7422b0303b589b">applyMappingMAD_64_32</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>, <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>, <a href="#a61f99fec329ba9cbb633996ee0452363">getInstrMappingForLoad</a>, <a href="#a941f1e23c69340ff634ea8bbb015e6d0">getValueMappingForPtr</a>, <a href="#a5f5e4d60d30f6101d9aedbc3e0e13bc0">handleD16VData</a>, <a href="#a7ebf01237ea354d0baf26fae2f0a04a3">isScalarLoadLegal</a> and <a href="#a0924254734e306adcc8cdcd0e2a3544c">splitBufferOffsets</a>.</p>

</div>
</div>

### TII {#a774f70ec47e4b324901ebbb23573157d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* llvm::AMDGPURegisterBankInfo::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="#a542fc1282cd157921c7f0900b73c63dd">AMDGPURegisterBankInfo</a>, <a href="#a67457fbc2d167a5a1a18124bd446278f">applyMappingBFE</a>, <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a> and <a href="#a8532a373e31385aa7f7ff3c4d14eff4b">setBufferOffsets</a>.</p>

</div>
</div>

### TRI {#afef42b99585e128b23a4980bc0bc1824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo* llvm::AMDGPURegisterBankInfo::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a>.</p>


<p>Referenced by <a href="#a7af7bb833a1702eacc1b0974ee514698">addMappingFromTable</a>, <a href="#a542fc1282cd157921c7f0900b73c63dd">AMDGPURegisterBankInfo</a>, <a href="#a67457fbc2d167a5a1a18124bd446278f">applyMappingBFE</a>, <a href="#a0494e300dac616c8ca39b2dbc8b1276c">applyMappingDynStackAlloc</a>, <a href="#a66655fdd73a951d10ad6fb804f0fac98">applyMappingImpl</a>, <a href="#af693d8401a06eab53b8b5b2d6df05243">buildReadFirstLane</a>, <a href="#a1d33fd387b81b22c1074a78d30192fea">collectWaterfallOperands</a>, <a href="#aae9640a886bae2966a9b445fc869935f">constrainOpWithReadfirstlane</a>, <a href="#a533cd1035e03cdca3da433e98e77e430">executeInWaterfallLoop</a>, <a href="#acefa289ec10ccb3fb0a928a8609b3724">getAGPROpMapping</a>, <a href="#abb1babbd49300ea60d3fe16eb5472749">getDefaultMappingAllVGPR</a>, <a href="#aba8269780a1b283db0509e18d3f99d92">getDefaultMappingSOP</a>, <a href="#ae6a779141ce10443d7b7d15b7ca76160">getDefaultMappingVOP</a>, <a href="#a27d74d69cbd37e794e77ff37aa8d3401">getImageMapping</a>, <a href="#ab65adad01ce4004d6fe95c5b740190ab">getInstrAlternativeMappings</a>, <a href="#abb21f77ed3dc15eb330b93b3efaa94ba">getInstrMapping</a>, <a href="#a61f99fec329ba9cbb633996ee0452363">getInstrMappingForLoad</a>, <a href="#a9561c2ca7dd4fcd8cf869156fbc79d79">getMappingType</a>, <a href="#a53fe77055b01a82e1a53e7798cef110a">getRegBankFromRegClass</a>, <a href="#a5bc45f557d3d69066e2c03a39ca51793">getRegBankID</a>, <a href="#a854d61301ea33c4f27021c50ae9e8bdf">getSGPROpMapping</a>, <a href="#a941f1e23c69340ff634ea8bbb015e6d0">getValueMappingForPtr</a>, <a href="#a6dca2bae7706ebd6d1d1681137040243">getVGPROpMapping</a>, <a href="#af5a764fec0343cb91d369059651a11e4">isSALUMapping</a>, <a href="#a8532a373e31385aa7f7ff3c4d14eff4b">setBufferOffsets</a> and <a href="#a909ca36ce602ebf9224694d163064009">split64BitValueForMapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp">AMDGPURegisterBankInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-h">AMDGPURegisterBankInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
