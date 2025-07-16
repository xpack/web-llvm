---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LegalizerHelper.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">llvm/CodeGen/GlobalISel/LegalizerHelper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">llvm/CodeGen/GlobalISel/GISelChangeObserver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">llvm/CodeGen/GlobalISel/GISelKnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">llvm/CodeGen/GlobalISel/LegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/lostdebuglocobserver-h">llvm/CodeGen/GlobalISel/LostDebugLocObserver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/mipatternmatch-h">llvm/CodeGen/GlobalISel/MIPatternMatch.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/machineirbuilder-h">llvm/CodeGen/GlobalISel/MachineIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">llvm/CodeGen/GlobalISel/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/lowleveltypeutils-h">llvm/CodeGen/LowLevelTypeUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/runtimelibcallutil-h">llvm/CodeGen/RuntimeLibcallUtil.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetframelowering-h">llvm/CodeGen/TargetFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetopcodes-h">llvm/CodeGen/TargetOpcodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include &lt;numeric&gt;
#include &lt;optional&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; int, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a> (LLT OrigTy, LLT NarrowTy, LLT &amp;LeftoverTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to break down <span class="doxyComputerOutput">OrigTy</span> into <span class="doxyComputerOutput">NarrowTy</span> sized pieces. <a href="#aabc73c20ee69fa5d4e1cb3318c074963">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af297fe5d0800d4319a7ca39cc7128f1a">getFloatTypeForLLT</a> (LLVMContext &amp;Ctx, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd00405fe4d2eca789c1225e75bc53f">getUnmergeResults</a> (SmallVectorImpl&lt; Register &gt; &amp;Regs, const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the result registers of G_UNMERGE_VALUES <span class="doxyComputerOutput">MI</span> to <span class="doxyComputerOutput">Regs</span>. <a href="#acbd00405fe4d2eca789c1225e75bc53f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316be66b059419e22aefc98fd49e1081">getRTLibDesc</a> (unsigned Opcode, unsigned Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad934d9334200ff676c9568774206cd">isLibCallInTailPosition</a> (const CallLowering::ArgInfo &amp;Result, MachineInstr &amp;MI, const TargetInstrInfo &amp;TII, MachineRegisterInfo &amp;MRI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if an instruction is in tail position in its caller. <a href="#a4ad934d9334200ff676c9568774206cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adc">LegalizerHelper::LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a4c274fa487db3aa41be87d492e19b">simpleLibcall</a> (MachineInstr &amp;MI, MachineIRBuilder &amp;MIRBuilder, unsigned Size, Type *OpType, LostDebugLocObserver &amp;LocObserver)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25a5ee99366e3b0d347b60918e6d51a6">getOutlineAtomicLibcall</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adc">LegalizerHelper::LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a> (MachineIRBuilder &amp;MIRBuilder, MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a> (unsigned Opcode, Type *ToType, Type *FromType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adc">LegalizerHelper::LegalizeResult</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3918a234a708d84f71e7eb9c07cff516">conversionLibcall</a> (MachineInstr &amp;MI, MachineIRBuilder &amp;MIRBuilder, Type *ToType, Type *FromType, LostDebugLocObserver &amp;LocObserver, const TargetLowering &amp;TLI, bool IsSigned=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa3c4eefe9983339cef7cd165b41dec9">getStateLibraryFunctionFor</a> (MachineInstr &amp;MI, const TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a50a0bab21f1d14a86a1483ec283e4447">RTLIB::Libcall</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4544044e58b9c4377b5eddfef5f6582f">getFCMPLibcallDesc</a> (const CmpInst::Predicate Pred, unsigned Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the corresponding libcall for the given Pred and the ICMP predicate that should be generated to compare with #0 after the libcall. <a href="#a4544044e58b9c4377b5eddfef5f6582f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944828d894ed9e13fbdfac2652d88745">getUnmergePieces</a> (SmallVectorImpl&lt; Register &gt; &amp;Pieces, MachineIRBuilder &amp;B, Register Src, LLT Ty)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f8ee7977675d9e8cdded7bda420b96e">emitLoadFromConstantPool</a> (Register DstReg, const Constant *ConstVal, MachineIRBuilder &amp;MIRBuilder)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f65ab13a2645935d21a119b722a55a1">getBitcastWiderVectorElementOffset</a> (MachineIRBuilder &amp;B, Register Idx, unsigned NewEltSize, unsigned OldEltSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Figure out the bit offset into a register when coercing a vector index for the wide element type. <a href="#a5f65ab13a2645935d21a119b722a55a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b99673a7e084ea8e75699f04b5f683a">buildBitFieldInsert</a> (MachineIRBuilder &amp;B, Register TargetReg, Register InsertReg, Register OffsetBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit code to insert <span class="doxyComputerOutput">InsertReg</span> into <span class="doxyComputerOutput">TargetRet</span> at <span class="doxyComputerOutput">OffsetBits</span> in <span class="doxyComputerOutput">TargetReg</span>, while preserving other bits in <span class="doxyComputerOutput">TargetReg</span>. <a href="#a2b99673a7e084ea8e75699f04b5f683a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16bdfa03e042a77b677e032fa495959">clampVectorIndex</a> (MachineIRBuilder &amp;B, Register IdxReg, LLT VecTy)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacaa5cd359fad565f73313045b5c83f0">hasSameNumEltsOnAllVectorOperands</a> (GenericMachineInstr &amp;MI, MachineRegisterInfo &amp;MRI, std::initializer_list&lt; unsigned &gt; NonVecOpIndices)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that all vector operands have same number of elements. <a href="#aacaa5cd359fad565f73313045b5c83f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a> (SmallVectorImpl&lt; DstOp &gt; &amp;DstOps, LLT Ty, unsigned NumElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill <span class="doxyComputerOutput">DstOps</span> with DstOps that have same number of elements combined as the Ty. <a href="#a74212fb91857a365ae5c6c85a0646d97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a497ca5acebfbe31e76e7c05991519336">broadcastSrcOp</a> (SmallVectorImpl&lt; SrcOp &gt; &amp;Ops, unsigned N, MachineOperand &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is used on <span class="doxyComputerOutput">N</span> sub-instructions. <a href="#a497ca5acebfbe31e76e7c05991519336">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced5d43b6a199d148e877d5536e95739">isNonZeroModBitWidthOrUndef</a> (const MachineRegisterInfo &amp;MRI, Register Reg, unsigned BW)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96bf442f65306b9a5ffda8ca473f0ce1">minMaxToCompare</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d7927ce19d14acc525d683585b8c58d">SwapN</a> (unsigned N, DstOp Dst, MachineIRBuilder &amp;B, MachineInstrBuilder Src, const APInt &amp;Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755eb2d2f25e8da3b2d904146e61b1a5">shouldLowerMemFuncForSize</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1476a89aa41e0a21b60bfc63a292f2c3">findGISelOptimalMemOpLowering</a> (std::vector&lt; LLT &gt; &amp;MemOps, unsigned Limit, const MemOp &amp;Op, unsigned DstAS, unsigned SrcAS, const AttributeList &amp;FuncAttributes, const TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f1d26ea9bced931d104b4dd8b26775f">getMemsetValue</a> (Register Val, LLT Ty, MachineIRBuilder &amp;MIB)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"legalizer"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12f4126914a32142bcfecc1e7bc0fe6e">RTLIBCASE_INT</a>(LibcallPrefix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb45c8a19296356de29272079557062">RTLIBCASE</a>(LibcallPrefix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(A, B)&nbsp;&nbsp;&nbsp;{<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_RELAX, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_REL, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ_REL}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7caf1b72b68025eb17420cc4663ad64d">LCALL5</a>(A)&nbsp;&nbsp;&nbsp;  <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 1), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 2), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 4), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 8), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 16)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c889b7be6822c2d4ad4d9eeeea768db">RTLIBCASE_CMP</a>(LibcallPrefix, ICmpPred)&nbsp;&nbsp;&nbsp;...</td>
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


<div class="doxySectionDef">

## Functions

### broadcastSrcOp() {#a497ca5acebfbe31e76e7c05991519336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void broadcastSrcOp (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/srcop">SrcOp</a> &gt; &amp; Ops, unsigned N, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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

<p>Operand <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> is used on <span class="doxyComputerOutput">N</span> sub-instructions.</p>


<p>Fill <span class="doxyComputerOutput">Ops</span> with <span class="doxyComputerOutput">N</span> SrcOps made from <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a></span> depending on operand type.</p>


<p>Definition at line 4833 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6d92157833612e9b4cd0085e181b7e">llvm::LegalizerHelper::fewerElementsVectorMultiEltType</a>.</p>

</div>
</div>

### buildBitFieldInsert() {#a2b99673a7e084ea8e75699f04b5f683a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register buildBitFieldInsert (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TargetReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> InsertReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> OffsetBits)</td>
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

<p>Emit code to insert <span class="doxyComputerOutput">InsertReg</span> into <span class="doxyComputerOutput">TargetRet</span> at <span class="doxyComputerOutput">OffsetBits</span> in <span class="doxyComputerOutput">TargetReg</span>, while preserving other bits in <span class="doxyComputerOutput">TargetReg</span>.</p>


<p>(InsertReg &lt;&lt; Offset) | (TargetReg &amp; ~(-1 &gt;&gt; InsertReg.size()) &lt;&lt; Offset)</p>


<p>Definition at line 3665 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a37f8fb6797142b53677bc4b59bf540">llvm::LegalizerHelper::bitcastInsertVectorElt</a>.</p>

</div>
</div>

### clampVectorIndex() {#ab16bdfa03e042a77b677e032fa495959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register clampVectorIndex (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> IdxReg, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> VecTy)</td>
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



<p>Definition at line 4722 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad960e1ff48d25c382b6d28e7961f074e">llvm::APInt::getLowBitsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#a441b9fc17e390be4c8dc6a1f1dd3d424">llvm::MIPatternMatch::m_ICst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mipatternmatch/#aa9bd186f4281a367fb872d17d0e7728b">llvm::MIPatternMatch::mi_match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae91b4ff9d9c084c672f78adb9ed4006a">llvm::LegalizerHelper::getVectorElementPointer</a>.</p>

</div>
</div>

### conversionLibcall() {#a3918a234a708d84f71e7eb9c07cff516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult conversionLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToType, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromType, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, bool IsSigned=false)</td>
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



<p>Definition at line 884 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/basearginfo/#a199d61df156e7d358ec1f18205615b1b">llvm::CallLowering::BaseArgInfo::Flags</a>, <a href="#ab6fa4a61feadaf493e383ab28709d486">getConvRTLibDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#add1aa3983c29592462326ecce44103e6">llvm::TargetLoweringBase::shouldSignExtendTypeInLibCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>.</p>

</div>
</div>

### createAtomicLibcall() {#aa386a0afb3210b56c30181f93a434ed3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult createAtomicLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a4b2fab18274c6ca276053bb774c6e8c3">llvm::MachineIRBuilder::buildSub</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af474773f09e4dbbc430d8d8df632e9fb">llvm::MachineIRBuilder::buildXor</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a2871c33d3a1264270d23ec72b71f1399">llvm::MachineOperand::CreateES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">llvm::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/structtype/#a18fc4545474c6ebb6f7c547f64f4fb31">llvm::StructType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#a9263ace85b7b15b4c903861b1f95e070">llvm::TargetSubtargetInfo::getCallLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a9fffac2512fe651f0d5e37e27f5bd51c">llvm::Function::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#abdbb44946a6951b5d90dd5313023156f">llvm::MCInstrInfo::getName</a>, <a href="#a25a5ee99366e3b0d347b60918e6d51a6">getOutlineAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#ade3f0d8b35d67c43df9425bb730a9a7c">llvm::TargetSubtargetInfo::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a35384c47e5ca9690216b1aa8fed5a8c9">llvm::MachineIRBuilder::getTII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca3d3565113157e799383dddc11c02ae31">llvm::LegalizerHelper::Legalized</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a97444fdd32d8610e39f82294399f3adca8e4cde53763caadd95a5eeaeb48344bf">llvm::LegalizerHelper::UnableToLegalize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>.</p>

</div>
</div>

### emitLoadFromConstantPool() {#a8f8ee7977675d9e8cdded7bda420b96e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitLoadFromConstantPool (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * ConstVal, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder)</td>
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



<p>Definition at line 3422 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a1da8389b4eb951b11309c28ad492e8d4">llvm::MachineIRBuilder::buildConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeede510b1aaac978daaba60dcc2817de">llvm::MachineIRBuilder::buildLoadInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aba1fee9e9c9b537fd2a02f33f714ca68">llvm::MachineFunction::getConstantPool</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#a8b1a64bd0c1be7a99998055c78d1312b">llvm::MachinePointerInfo::getConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool/#afd6691ddb5d4adf50d744297e18a1c6d">llvm::MachineConstantPool::getConstantPoolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#aeb6d0a9254bc3183046873436fc7c12e">llvm::MachineIRBuilder::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a453ae3052b4f5b14cb4c184243ce5027">llvm::MachineFunction::getMachineMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a9ec04f3692b9601036d2d4477c4c3749">llvm::MachineIRBuilder::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/classes/llvm/llt/#a7ff0361855acbbe71b15b8dc6003fbc5">llvm::LLT::pointer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aefeacc46707017018d95faf6751da717">llvm::LegalizerHelper::lowerConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a297f161b2970f693a98a4bf30c7eb630">llvm::LegalizerHelper::lowerFConstant</a>.</p>

</div>
</div>

### findGISelOptimalMemOpLowering() {#a1476a89aa41e0a21b60bfc63a292f2c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findGISelOptimalMemOpLowering (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &gt; &amp; MemOps, unsigned Limit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memop">MemOp</a> &amp; Op, unsigned DstAS, unsigned SrcAS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; FuncAttributes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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



<p>Definition at line 9457 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a63b5343b9da17f8bcc83ec545022f5c7">llvm::TargetLoweringBase::allowsMisalignedMemoryAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae22967d11b695d268992470debfae4b2">llvm::bit_floor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38d317b55a165bcddde7bb58ab7b12f3">llvm::getMVTForLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a64db465f835b214b79cb525a9326062d">llvm::TargetLoweringBase::getOptimalMemOpLLT</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddac2989bebe46c9b9fcb7a92e5ade8dde6">llvm::MachineMemOperand::MONone</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getBitcastWiderVectorElementOffset() {#a5f65ab13a2645935d21a119b722a55a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register getBitcastWiderVectorElementOffset (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Idx, unsigned NewEltSize, unsigned OldEltSize)</td>
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

<p>Figure out the bit offset into a register when coercing a vector index for the wide element type.</p>


<p>This is only for the case when promoting vector to one with larger elements. offset_idx = G_AND idx, ~(-1 &lt;&lt; Log2(DstEltSize / SrcEltSize)) offset_bits = G_SHL offset_idx, Log2(SrcEltSize)</p>


<p>Definition at line 3537 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a071e8d814b2b30b02544fad964227b8e">llvm::APInt::getAllOnes</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a646986783f35e0fef8988f0f28d2589f">llvm::Log2_32</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ac50dd9fe6220347f8306e3694a8129cb">llvm::LegalizerHelper::bitcastExtractVectorElt</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0a37f8fb6797142b53677bc4b59bf540">llvm::LegalizerHelper::bitcastInsertVectorElt</a>.</p>

</div>
</div>

### getConvRTLibDesc() {#ab6fa4a61feadaf493e383ab28709d486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall getConvRTLibDesc (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ToType, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * FromType)</td>
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



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#ab82ac391f77e4b35af455c9c1f9d7fba">llvm::RTLIB::getFPEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#aba26b1883eac90bc8f0c2b51a5377545">llvm::RTLIB::getFPROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#aa70a6cd6c880ca47e604870efe33eba4">llvm::RTLIB::getFPTOSINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a80e747e8b302cf5ad8e1d5ecade1937c">llvm::RTLIB::getFPTOUINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a11ba84d43a1ba5d6c1e1c645d34a0dd9">llvm::RTLIB::getSINTTOFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/rtlib/#a3c139798e0933ade84b12ac860b593de">llvm::RTLIB::getUINTTOFP</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a56bb53e2d0b01c78c8c538f903fd45b8">llvm::MVT::getVT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a3918a234a708d84f71e7eb9c07cff516">conversionLibcall</a>.</p>

</div>
</div>

### getFCMPLibcallDesc() {#a4544044e58b9c4377b5eddfef5f6582f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; RTLIB::Libcall, CmpInst::Predicate &gt; getFCMPLibcallDesc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred, unsigned Size)</td>
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

<p>Returns the corresponding libcall for the given Pred and the ICMP predicate that should be generated to compare with #0 after the libcall.</p>

<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba07aee43ffb66908a25c55c77ce4c0d05">llvm::CmpInst::BAD_ICMP_PREDICATE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="#a0c889b7be6822c2d4ad4d9eeeea768db">RTLIBCASE_CMP</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getFloatTypeForLLT() {#af297fe5d0800d4319a7ca39cc7128f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * getFloatTypeForLLT (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#acb145f988329d1d621f73abcafea21d8">llvm::Type::getDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ad5e0fe0efdd88f98a5b5eb512d5351c2">llvm::Type::getFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a49f37835a410e050b960dd936a54dd05">llvm::Type::getFP128Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ae550f2e9436b395b614b4377ba27007f">llvm::Type::getHalfTy</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ace5611e40c0a2dbdc2c6cbc93bea180c">llvm::Type::getX86_FP80Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>.</p>

</div>
</div>

### getMemsetValue() {#a2f1d26ea9bced931d104b4dd8b26775f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register getMemsetValue (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIB)</td>
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



<p>Definition at line 9523 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a31a4848346777be4c13b39d57c0885d0">llvm::MachineIRBuilder::buildMul</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a55bde2ba6aacac745a29a7e50c6be007">llvm::MachineIRBuilder::buildSplatBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7ac5295bdfdd480a2c66ee54273ebe21">llvm::MachineIRBuilder::buildZExtOrTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad7322f56c0659b8dc8e55567767b74d6">llvm::MachineIRBuilder::getMRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a1c5fadb14ff1d77faad0cb58a43252ab">llvm::MachineInstrBuilder::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8c55d8510ad4b7cb957d8f5a7cd6944e">llvm::APInt::getSplat</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>.</p>

</div>
</div>

### getNarrowTypeBreakDown() {#aabc73c20ee69fa5d4e1cb3318c074963}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; int, int &gt; getNarrowTypeBreakDown (<a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> OrigTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> NarrowTy, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> &amp; LeftoverTy)</td>
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

<p>Try to break down <span class="doxyComputerOutput">OrigTy</span> into <span class="doxyComputerOutput">NarrowTy</span> sized pieces.</p>


<p>Returns the number of <span class="doxyComputerOutput">NarrowTy</span> elements needed to reconstruct <span class="doxyComputerOutput">OrigTy</span>, with any leftover piece as type <span class="doxyComputerOutput">LeftoverTy</span></p>


<p>Returns -1 in the first element of the pair if the breakdown is not satisfiable.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#aa24450f600cabd7212bd264a6dbc190c">llvm::LLT::getElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a67021459c7ef8f9a634b4eac7ffd0f96">llvm::LLT::scalar</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae74a60e5edcee0609a1e4fddc62a8a01">llvm::LLT::scalarOrVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>.</p>

</div>
</div>

### getOutlineAtomicLibcall() {#a25a5ee99366e3b0d347b60918e6d51a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall getOutlineAtomicLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#ae456a811703836ee5d9e32c3e51a15b6">llvm::LLT::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="#a7caf1b72b68025eb17420cc4663ad64d">LCALL5</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>.</p>

</div>
</div>

### getRTLibDesc() {#a316be66b059419e22aefc98fd49e1081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall getRTLibDesc (unsigned Opcode, unsigned Size)</td>
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



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aecb45c8a19296356de29272079557062">RTLIBCASE</a>, <a href="#a12f4126914a32142bcfecc1e7bc0fe6e">RTLIBCASE_INT</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a> and <a href="#a57a4c274fa487db3aa41be87d492e19b">simpleLibcall</a>.</p>

</div>
</div>

### getStateLibraryFunctionFor() {#aaa3c4eefe9983339cef7cd165b41dec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RTLIB::Libcall getStateLibraryFunctionFor (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getUnmergePieces() {#a944828d894ed9e13fbdfac2652d88745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getUnmergePieces (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Pieces, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Src, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty)</td>
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



<p>Definition at line 3415 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6fb535803cbc7430528cdb19a157dd47">llvm::LegalizerHelper::lowerBitcast</a>.</p>

</div>
</div>

### getUnmergeResults() {#acbd00405fe4d2eca789c1225e75bc53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getUnmergeResults (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &gt; &amp; Regs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Append the result registers of G_UNMERGE_VALUES <span class="doxyComputerOutput">MI</span> to <span class="doxyComputerOutput">Regs</span>.</p>

<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### hasSameNumEltsOnAllVectorOperands() {#aacaa5cd359fad565f73313045b5c83f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasSameNumEltsOnAllVectorOperands (<a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, std::initializer_list&lt; unsigned &gt; NonVecOpIndices)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> that all vector operands have same number of elements.</p>


<p>Other operands should be listed in NonVecOp.</p>


<p>Definition at line 4772 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/llt/#a71181d67d0bf68c3b8a535ec20463f90">llvm::LLT::getNumElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a7da5cc6e8aadd4d5fb6dd68f8ec12b7e">llvm::LLT::isVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6d92157833612e9b4cd0085e181b7e">llvm::LegalizerHelper::fewerElementsVectorMultiEltType</a>.</p>

</div>
</div>

### isLibCallInTailPosition() {#a4ad934d9334200ff676c9568774206cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isLibCallInTailPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">CallLowering::ArgInfo</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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

<p>True if an instruction is in tail position in its caller.</p>


<p>Intended for legalizing libcalls as tail calls when possible.</p>


<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a5604157867b3d226260f6388b987e49a">llvm::AttributeList::getRetAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a4cf3cb56358d18065c78992569c32d2f">llvm::AttrBuilder::hasAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#afe4e348d7ff2f6b76dcaa69382b78980">llvm::AttributeList::hasRetAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0270bdca4aeb43f39bf91c900a398057">llvm::next_nodbg</a>, <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#aa63e528eeff5082f6920b10244143920">llvm::AttrBuilder::removeAttribute</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>.</p>

</div>
</div>

### isNonZeroModBitWidthOrUndef() {#aced5d43b6a199d148e877d5536e95739}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNonZeroModBitWidthOrUndef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, unsigned BW)</td>
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



<p>Definition at line 7157 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#af7e1934ed72a405ef073ea5f9bbe828e">llvm::ConstantInt::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a50bf4f84c8a910409d92dd85e2b72953">llvm::matchUnaryPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a4e3a2187cacdec76028617a403c47d89">llvm::APInt::urem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a0c43f88b7b733fa84bb93583d9163b54">expandVPFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a7359ee87521122d9315cb47df7ec57c5">llvm::LegalizerHelper::lowerFunnelShiftAsShifts</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a332b012f0983179618526234e605c9aa">llvm::LegalizerHelper::lowerFunnelShiftWithInverse</a>.</p>

</div>
</div>

### makeDstOps() {#a74212fb91857a365ae5c6c85a0646d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void makeDstOps (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> &gt; &amp; DstOps, <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> Ty, unsigned NumElts)</td>
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

<p>Fill <span class="doxyComputerOutput">DstOps</span> with DstOps that have same number of elements combined as the Ty.</p>


<p>These DstOps have either scalar type when <span class="doxyComputerOutput">NumElts</span> = 1 or are vectors with <span class="doxyComputerOutput">NumElts</span> elements. When Ty.getNumElements() is not multiple of <span class="doxyComputerOutput">NumElts</span> last <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> (leftover) has fewer then <span class="doxyComputerOutput">NumElts</span> elements.</p>


<p>Definition at line 4810 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#acd1eca3232b7b3072543294cd2377a37">llvm::LLT::fixed_vector</a>, <a href="#aabc73c20ee69fa5d4e1cb3318c074963">getNarrowTypeBreakDown</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6d92157833612e9b4cd0085e181b7e">llvm::LegalizerHelper::fewerElementsVectorMultiEltType</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a60e4161d46b020a55403acd13e31df9a">llvm::LegalizerHelper::fewerElementsVectorPhi</a>.</p>

</div>
</div>

### minMaxToCompare() {#a96bf442f65306b9a5ffda8ca473f0ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CmpInst::Predicate minMaxToCompare (unsigned Opc)</td>
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



<p>Definition at line 8007 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a7287c6cc84f805db4ae46d581b4deecc">llvm::LegalizerHelper::lowerMinMax</a>.</p>

</div>
</div>

### shouldLowerMemFuncForSize() {#a755eb2d2f25e8da3b2d904146e61b1a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldLowerMemFuncForSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 9447 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a548cfb9440f36ba67fc5566b8e967fc6">llvm::Function::hasMinSize</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a1c455e007178a24dfb18ac0e200ea02c">llvm::Function::hasOptSize</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#ab6fdf9b428bc3d57837022121c155cbf">llvm::Triple::isOSDarwin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aca820b14c7ae2e658cefd8a3be4da035">llvm::LegalizerHelper::lowerMemCpyFamily</a>.</p>

</div>
</div>

### simpleLibcall() {#a57a4c274fa487db3aa41be87d492e19b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LegalizerHelper::LegalizeResult simpleLibcall (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; MIRBuilder, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OpType, <a href="/web-llvm/docs/api/classes/llvm/lostdebuglocobserver">LostDebugLocObserver</a> &amp; LocObserver)</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8829536a23c01dcd3a6017dccb148c90">llvm::createLibcall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#a316be66b059419e22aefc98fd49e1081">getRTLibDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/legalizeactions/#a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e">llvm::LegalizeActions::Libcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad8a495f4190353f60d1cd5e471283f40">llvm::LegalizerHelper::libcall</a>.</p>

</div>
</div>

### SwapN() {#a7d7927ce19d14acc525d683585b8c58d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder SwapN (unsigned N, <a href="/web-llvm/docs/api/classes/llvm/dstop">DstOp</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> Src, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Mask)</td>
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



<p>Definition at line 8959 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ed659cad017d524d63d763e19ef756f">llvm::LegalizerHelper::lowerBitreverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"legalizer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### LCALL5 {#a7caf1b72b68025eb17420cc4663ad64d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LCALL5(A)&nbsp;&nbsp;&nbsp;  <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 1), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 2), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 4), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 8), <a href="#a170d2ae878fd8d8d7d558956f1dd6510">LCALLS</a>(<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, 16)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>Referenced by <a href="#a25a5ee99366e3b0d347b60918e6d51a6">getOutlineAtomicLibcall</a>.</p>

</div>
</div>

### LCALLS {#a170d2ae878fd8d8d7d558956f1dd6510}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LCALLS(A, B)&nbsp;&nbsp;&nbsp;{<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_RELAX, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_REL, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>##<a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>##_ACQ_REL}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>

</div>
</div>

### RTLIBCASE {#aecb45c8a19296356de29272079557062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTLIBCASE(LibcallPrefix)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    switch (<a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>) {                                                            \
    case 32:                                                                   \
      return RTLIB::LibcallPrefix##32;                                         \
    case 64:                                                                   \
      return RTLIB::LibcallPrefix##64;                                         \
    case 80:                                                                   \
      return RTLIB::LibcallPrefix##80;                                         \
    case 128:                                                                  \
      return RTLIB::LibcallPrefix##128;                                        \
    default:                                                                   \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>("unexpected size");                                     \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>Referenced by <a href="#a316be66b059419e22aefc98fd49e1081">getRTLibDesc</a>.</p>

</div>
</div>

### RTLIBCASE\_CMP {#a0c889b7be6822c2d4ad4d9eeeea768db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTLIBCASE_CMP(LibcallPrefix, ICmpPred)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    switch (<a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>) {                                                            \
    case 32:                                                                   \
      return {RTLIB::LibcallPrefix##32, ICmpPred};                             \
    case 64:                                                                   \
      return {RTLIB::LibcallPrefix##64, ICmpPred};                             \
    case 128:                                                                  \
      return {RTLIB::LibcallPrefix##128, ICmpPred};                            \
    default:                                                                   \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>("unexpected size");                                     \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 1016 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>Referenced by <a href="#a4544044e58b9c4377b5eddfef5f6582f">getFCMPLibcallDesc</a>.</p>

</div>
</div>

### RTLIBCASE\_INT {#a12f4126914a32142bcfecc1e7bc0fe6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTLIBCASE_INT(LibcallPrefix)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  do {                                                                         \
    switch (<a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>) {                                                            \
    case 32:                                                                   \
      return RTLIB::LibcallPrefix##32;                                         \
    case 64:                                                                   \
      return RTLIB::LibcallPrefix##64;                                         \
    case 128:                                                                  \
      return RTLIB::LibcallPrefix##128;                                        \
    default:                                                                   \
      <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>("unexpected size");                                     \
    }                                                                          \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp">LegalizerHelper.cpp</a>.</p>


<p>Referenced by <a href="#a316be66b059419e22aefc98fd49e1081">getRTLibDesc</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
