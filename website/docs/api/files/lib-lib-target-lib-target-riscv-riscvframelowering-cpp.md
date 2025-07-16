---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVFrameLowering.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-h">RISCVFrameLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmachinefunctioninfo-h">RISCVMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvsubtarget-h">RISCVSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">llvm/CodeGen/LivePhysRegs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/registerscavenging-h">llvm/CodeGen/RegisterScavenging.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/diagnosticinfo-h">llvm/IR/DiagnosticInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/leb128-h">llvm/Support/LEB128.h</a>"
#include &lt;algorithm&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvframelowering-cpp-">anonymous{RISCVFrameLowering.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfisaveregisteremitter">CFISaveRegisterEmitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvframelowering-cpp-/cfirestoreregisteremitter">CFIRestoreRegisterEmitter</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51d8ccc37acb885f5b25675d4b06582">getABIStackAlignment</a> (RISCVABI::ABI ABI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MI, const DebugLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bf4f9d1247175b3a6e0def631bda61b">getSpillLibCallName</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392d167565f63198879bcfedd3ac419d">getRestoreLibCallName</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcee7be41e609e2b3e3239648007832">getPushPopEncodingAndNum</a> (const Register MaxReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ad01c7c2990a944ca190cd409a60d5">getMaxPushPopReg</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab858e12b9896856aca708f103f94e8b7">getPushOrLibCallsSavedInfo</a> (const MachineFunction &amp;MF, const std::vector&lt; CalleeSavedInfo &gt; &amp;CSI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3defde95d12941aee71bb6f17a7b6e">appendScalableVectorExpression</a> (const TargetRegisterInfo &amp;TRI, SmallVectorImpl&lt; char &gt; &amp;Expr, int FixedOffset, int ScalableOffset, llvm::raw_string_ostream &amp;Comment)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a> (const TargetRegisterInfo &amp;TRI, Register Reg, uint64_t FixedOffset, uint64_t ScalableOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction">MCCFIInstruction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a> (const TargetRegisterInfo &amp;TRI, Register Reg, uint64_t FixedOffset, uint64_t ScalableOffset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59f353dd1adb78d8e0187803c5edb83">getScavSlotsNumForRVV</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e2c07f0563d2e32c68a2fd08d716b0">hasRVVFrameObject</a> (const MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72d59e703230d33686b9e5b1c0973ea">estimateFunctionSizeInBytes</a> (const MachineFunction &amp;MF, const RISCVInstrInfo &amp;TII)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7198fb940b94e99d884e48a2355ffb5">getCalleeSavedRVVNumRegs</a> (const Register &amp;BaseReg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d536cb0afee47ed6a6fcbef2c85cfe3">getRVVBaseRegister</a> (const RISCVRegisterInfo &amp;TRI, const Register &amp;Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a> (MachineFunction &amp;MF, MachineBasicBlock &amp;MBB, MachineBasicBlock::iterator MBBI, DebugLoc DL, Register TargetReg, bool IsRVV)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a> = RISCV::X8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a> = RISCV::X2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a> = RISCV::X1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, int8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a810744cdd1df25a6c262b32a99b29917">FixedCSRFIMap</a>[] = ...</td>
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

### appendScalableVectorExpression() {#a9e3defde95d12941aee71bb6f17a7b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void appendScalableVectorExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Expr, int FixedOffset, int ScalableOffset, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">llvm::raw_string_ostream</a> &amp; Comment)</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a> and <a href="#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>.</p>

</div>
</div>

### createDefCFAExpression() {#a89565d08a98c901e24daed37f35cd442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction createDefCFAExpression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, uint64_t FixedOffset, uint64_t ScalableOffset)</td>
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



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="#a9e3defde95d12941aee71bb6f17a7b6e">appendScalableVectorExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### createDefCFAOffset() {#af7b1b04b85a4e865d887cbf6f5889a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCCFIInstruction createDefCFAOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg, uint64_t FixedOffset, uint64_t ScalableOffset)</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="#a9e3defde95d12941aee71bb6f17a7b6e">appendScalableVectorExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### emitSCSEpilogue() {#adcff3487a7ab24e32ed892aedf767cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitSCSEpilogue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#a43cce47857fdb1dfec97aeba83ab82a3">llvm::MCCFIInstruction::createRestore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a4e4e6764dc61dbf0e8f330644880480f">llvm::MachineInstr::FrameDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo/#ac6386cc5d6721871608b96a12a28b3c0">llvm::CalleeSavedInfo::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a7554ec1d1735879427a93276e4de1a38">llvm::RISCVABI::getSCSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>.</p>

</div>
</div>

### emitSCSPrologue() {#acf179a5b6cfdcd80b458b93d503e0ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitSCSPrologue (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp; DL)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a3e4e67777edb24fac492ef4ae15e69ba">llvm::MachineInstrBuilder::addCFIIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a247230f547064b27022d70c0aeb86682">llvm::MachineFunction::addFrameInst</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/mccfiinstruction/#ac6eb36207cf2c7ebbd9a67e63dcc5568">llvm::MCCFIInstruction::createEscape</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#aad474502cac7b22b83e74de089f8c81d">llvm::MachineFrameInfo::getCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo/#ac6386cc5d6721871608b96a12a28b3c0">llvm::CalleeSavedInfo::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a7554ec1d1735879427a93276e4de1a38">llvm::RISCVABI::getSCSPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#afb28a4deafe2954b0534cc6399ce518b">llvm::Function::hasFnAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a632680dcf899466c32c0095a40e7e89e">llvm::MachineInstrBuilder::setMIFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### emitStackProbeInline() {#a30a608df0c31b4ad3814cce66364082c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitStackProbeInline (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> MBBI, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> TargetReg, bool IsRVV)</td>
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



<p>Definition at line 2138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a935e2a8884592189d8f261634a0b24c5">llvm::MachineBasicBlock::addSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#adfc62ee16549afaac5bde30156ddc989">llvm::MachineFunction::CreateMachineBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a78f1067d270179dff7915b90a03ce237">llvm::MachineInstr::FrameSetup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5f6b149b3f5ee5ed6ad7db9b58b148">llvm::fullyRecomputeLiveIns</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#afdb244cc3da7d9ac6bc08afcbc4e3633">llvm::RISCVTargetLowering::getStackProbeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af4c0db6d503e0ba3b8e44067023ffbba">llvm::MachineFunction::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#adf25b569ca308aacc819a2331626ed5d">llvm::MachineInstrBuilder::setMIFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#adf0023bdc4f05a7849c35b1c859580d8">llvm::MachineBasicBlock::splice</a>, <a href="#a0e92b710da2e75e063fee5f7efb8f21e">SPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a046a35e36c4c1206711ea82ee9cb6d72">llvm::MachineBasicBlock::transferSuccessorsAndUpdatePHIs</a>.</p>

</div>
</div>

### estimateFunctionSizeInBytes() {#aa72d59e703230d33686b9e5b1c0973ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned estimateFunctionSizeInBytes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo">RISCVInstrInfo</a> &amp; TII)</td>
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



<p>Definition at line 1568 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a0aa4dfd381666516aca9f87ba54353b7">llvm::RISCVSubtarget::hasStdExtCOrZca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>.</p>

</div>
</div>

### getABIStackAlignment() {#ab51d8ccc37acb885f5b25675d4b06582}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align getABIStackAlignment (<a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9">RISCVABI::ABI</a> ABI)</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9a9e062b1814798f2a29e2b28e74a36bc1">llvm::RISCVABI::ABI_ILP32E</a> and <a href="/web-llvm/docs/api/namespaces/llvm/riscvabi/#a11c6ee2d4e18ec16c570243cc285c7e9adc7da95e1193beba354466672c1cdb38">llvm::RISCVABI::ABI_LP64E</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#af893429fa90ab18cd29ed194fd04fdf6">llvm::RISCVFrameLowering::RISCVFrameLowering</a>.</p>

</div>
</div>

### getCalleeSavedRVVNumRegs() {#aa7198fb940b94e99d884e48a2355ffb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCalleeSavedRVVNumRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; BaseReg)</td>
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



<p>Definition at line 1922 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>

</div>
</div>

### getLibCallID() {#ac4353ee1069000ba0e78e584368bf1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getLibCallID (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afcfb1380ec9ff3f6106193a6ea9313c6">llvm::Register::id</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="#a392d167565f63198879bcfedd3ac419d">getRestoreLibCallName</a> and <a href="#a4bf4f9d1247175b3a6e0def631bda61b">getSpillLibCallName</a>.</p>

</div>
</div>

### getMaxPushPopReg() {#ae4ad01c7c2990a944ca190cd409a60d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register getMaxPushPopReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#a810744cdd1df25a6c262b32a99b29917">FixedCSRFIMap</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#afcfb1380ec9ff3f6106193a6ea9313c6">llvm::Register::id</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### getPushOrLibCallsSavedInfo() {#ab858e12b9896856aca708f103f94e8b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; CalleeSavedInfo, 8 &gt; getPushOrLibCallsSavedInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="#a810744cdd1df25a6c262b32a99b29917">FixedCSRFIMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getPushPopEncodingAndNum() {#a7bcee7be41e609e2b3e3239648007832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; getPushPopEncodingAndNum (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> MaxReg)</td>
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



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5ae7ab1a212f15abd8348b30007f66c1af">llvm::RISCVZC::RA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a8ed1eda3896fa43338e7d230a0a4993d">llvm::RISCVZC::RA_S0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a187af652b39061ed41d0b62352661f32">llvm::RISCVZC::RA_S0_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a5ab1e5a9b1ba4f448389be88afcb5127">llvm::RISCVZC::RA_S0_S11</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a31e3e9d613967296c388d36615f6f97d">llvm::RISCVZC::RA_S0_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5aadd2972b9caac589722230f8a0e765eb">llvm::RISCVZC::RA_S0_S3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5ac17ab07c26d45484136905fd4399b743">llvm::RISCVZC::RA_S0_S4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a0171e14e615b8a32d8e0144f6857f4f3">llvm::RISCVZC::RA_S0_S5</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a43ef1bb5618a7dfec8447935265bc7a3">llvm::RISCVZC::RA_S0_S6</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a5fc8d3f95877d92dac0387673be112f4">llvm::RISCVZC::RA_S0_S7</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a3150087b02a06cf72986c42415be65d7">llvm::RISCVZC::RA_S0_S8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvzc/#a828db3401ee4af8cdef6f92bf07c51c5a3b4cce13ba862cdd68e4ef5c7262745c">llvm::RISCVZC::RA_S0_S9</a> and <a href="#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>.</p>

</div>
</div>

### getRestoreLibCallName() {#a392d167565f63198879bcfedd3ac419d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getRestoreLibCallName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Reference <a href="#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a>.</p>

</div>
</div>

### getRVVBaseRegister() {#a2d536cb0afee47ed6a6fcbef2c85cfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister getRVVBaseRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo">RISCVRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; Reg)</td>
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



<p>Definition at line 1929 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

### getRVVCalleeSavedInfo() {#a857ca8ebd4e64059aa8774f14445e414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; CalleeSavedInfo, 8 &gt; getRVVCalleeSavedInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getScavSlotsNumForRVV() {#af59f353dd1adb78d8e0187803c5edb83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getScavSlotsNumForRVV (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 1505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a9227d5dccc1baf1834e4b98c5b9502e5">llvm::RISCVSubtarget::hasVInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#ad821f506ad146f3ed222dbdeb8c3ca06">llvm::RISCV::isRVVSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5a3c6a2a8f3cda71661a17a0df700e8f9c">llvm::TargetStackID::ScalableVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

### getSpillLibCallName() {#a4bf4f9d1247175b3a6e0def631bda61b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getSpillLibCallName (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Reference <a href="#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### getUnmanagedCSI() {#ae435b1b5b5ed85a029acf53fe157d437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; CalleeSavedInfo, 8 &gt; getUnmanagedCSI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/calleesavedinfo">CalleeSavedInfo</a> &gt; &amp; CSI)</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/targetstackid/#a71392100eb15ba746b1f898986f5d8a5af2af9eb94ff1bc08308bc738d744ee85">llvm::TargetStackID::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a54f334a9c8ca6d105eae383ae87e4524">llvm::MachineFunction::getFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ad718aae0ce2a188fa35cb2781024ffc0">llvm::MachineFrameInfo::getStackID</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### hasRVVFrameObject() {#a56e2c07f0563d2e32c68a2fd08d716b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasRVVFrameObject (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 1549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a682ca2f9a07f1d42cf4b7aa0e62fc569">llvm::RISCVFrameLowering::hasReservedCallFrame</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#ae380dabb206877f151fa2c3c39f9585a">llvm::RISCVFrameLowering::processFunctionBeforeFrameFinalized</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### FixedCSRFIMap {#a810744cdd1df25a6c262b32a99b29917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::pair&lt;MCPhysReg, int8_t&gt; FixedCSRFIMap[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    { <a href="#adb9ddd77a3cbc6e719b2ff77e0a2efcf">RAReg</a>, -1},       { <a href="#a1dd46e82704007e1b3b83ee229ffa79f">FPReg</a>, -2},
    { RISCV::X9, -3},   { RISCV::X18, -4},
    { RISCV::X19, -5},  { RISCV::X20, -6},
    { RISCV::X21, -7},  { RISCV::X22, -8},
    { RISCV::X23, -9},  { RISCV::X24, -10},
    { RISCV::X25, -11}, { RISCV::X26, -12},
    { RISCV::X27, -13}}
</div>
</dd>
</dl>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5a0c9359d4e969f68a7c7643fc3fcb5c">llvm::RISCVFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="#ae4ad01c7c2990a944ca190cd409a60d5">getMaxPushPopReg</a>, <a href="#ab858e12b9896856aca708f103f94e8b7">getPushOrLibCallsSavedInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a6658cff9efc100c5b2751bed442d5a9b">llvm::RISCVFrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a2d66c6615f09ca15ca384387a5d0eb3e">llvm::RISCVFrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### FPReg {#a1dd46e82704007e1b3b83ee229ffa79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register FPReg = RISCV::X8</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a3b9c6a6d8deeb4b38fe15c4bbfcfaced">llvm::M68kFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa2e3cf793a3ed0af11da73a0bfbb5ad1">llvm::RISCVFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a60f61ed13ff961051650fac4c6fa4ec0">llvm::CSKYFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a>, <a href="#a7bcee7be41e609e2b3e3239648007832">getPushPopEncodingAndNum</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#abcb33f3f153c050bf1a63bcd8223e836">llvm::PPCFrameLowering::replaceFPWithRealFP</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#adca65a5406a289a41bd58993e28bb3aa">llvm::Thumb1FrameLowering::restoreCalleeSavedRegisters</a> and <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>.</p>

</div>
</div>

### RAReg {#adb9ddd77a3cbc6e719b2ff77e0a2efcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register RAReg = RISCV::X1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa2e3cf793a3ed0af11da73a0bfbb5ad1">llvm::RISCVFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="#adcff3487a7ab24e32ed892aedf767cf1">emitSCSEpilogue</a>, <a href="#acf179a5b6cfdcd80b458b93d503e0ed0">emitSCSPrologue</a>, <a href="#ac4353ee1069000ba0e78e584368bf1f2">getLibCallID</a> and <a href="#a7bcee7be41e609e2b3e3239648007832">getPushPopEncodingAndNum</a>.</p>

</div>
</div>

### SPReg {#a0e92b710da2e75e063fee5f7efb8f21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register SPReg = RISCV::X2</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp">RISCVFrameLowering.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a0494e300dac616c8ca39b2dbc8b1276c">llvm::AMDGPURegisterBankInfo::applyMappingDynStackAlloc</a>, <a href="#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a32930048228d6d7aa610ee2ffd4721b5">llvm::CSKYFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a62610f9e2d92c706d2f8e0cc282512c1">llvm::LoongArchFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aeac33945153d277b7244196a35084006">llvm::RISCVFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#afb457df257778163977aebad1d1165e8">llvm::SIFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a7bafcec0aefe1c8144ce6cacdf80ff19">llvm::RISCVTargetLowering::emitDynamicProbedAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a702408ee868bae14b0de2b8a28c8058d">llvm::SIFrameLowering::emitEntryFunctionPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a60f61ed13ff961051650fac4c6fa4ec0">llvm::CSKYFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a586e88416ae37cf1579986caeb97a9fa">llvm::LoongArchFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a4bd38718f81e97d49ac056306d2efbab">llvm::SystemZXPLINKFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#adbe9a36b5d064d3fe4667e4c1b47af85">llvm::WebAssemblyFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a2cb46b1ded73af4c2924bd2d1d8db334">llvm::PPCTargetLowering::emitProbedAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a80326c86cd0c224fcea6c5b654870747">llvm::CSKYFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#af594db9b0cfd3cba7360a0f8246c0704">llvm::LoongArchFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ac78e4ff0f9a757b578b967d5bd1f70ee">llvm::WebAssemblyFrameLowering::emitPrologue</a>, <a href="#a30a608df0c31b4ad3814cce66364082c">emitStackProbeInline</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ab95d4485884d2e093f534590f24cfe0d">llvm::LegalizerHelper::getDynStackAllocTargetPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#a1de30cc152058819888b9d02619f16ac">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86calllowering-cpp-/x86outgoingvaluehandler/#a059b61bb0bab07b3cf7da0e06f5893dd">anonymous{X86CallLowering.cpp}::X86OutgoingValueHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/structs/m68koutgoingarghandler/#a202a7e2a16e7921c97c6767cb68bdae9">M68kOutgoingArgHandler::getStackAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a62e484f70a2007cfe30d42db868f84ab">llvm::PPCInstrInfo::isTOCSaveMI</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetlowering/#ad8f7466f773acb6c1c191bdf61978a76">llvm::LanaiTargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#abcceb75e0f115b68f1a484fd93b19f07">llvm::SITargetLowering::LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcisellowering-cpp/#a5a204a396ded16cd692c0dc91ce216f4">LowerDYNAMIC_STACKALLOC</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0b54c43cec90635e63e99f792b9207bc">llvm::LegalizerHelper::lowerDynStackAlloc</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
