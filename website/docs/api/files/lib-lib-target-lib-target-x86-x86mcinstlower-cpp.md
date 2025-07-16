---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86MCInstLower.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86attinstprinter-h">MCTargetDesc/X86ATTInstPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">MCTargetDesc/X86BaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">MCTargetDesc/X86EncodingOptimization.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86instcomments-h">MCTargetDesc/X86InstComments.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86shuffledecode-h">MCTargetDesc/X86ShuffleDecode.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86targetstreamer-h">MCTargetDesc/X86TargetStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-h">X86AsmPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86machinefunctioninfo-h">X86MachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86registerinfo-h">X86RegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86shuffledecodeconstantpool-h">X86ShuffleDecodeConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86subtarget-h">X86Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebranchprobabilityinfo-h">llvm/CodeGen/MachineBranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineconstantpool-h">llvm/CodeGen/MachineConstantPool.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfoimpls-h">llvm/CodeGen/MachineModuleInfoImpls.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/stackmaps-h">llvm/CodeGen/StackMaps.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mangler-h">llvm/IR/Mangler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccodeemitter-h">llvm/MC/MCCodeEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcexpr-h">llvm/MC/MCExpr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcfixup-h">llvm/MC/MCFixup.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinst-h">llvm/MC/MCInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstbuilder-h">llvm/MC/MCInstBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcstreamer-h">llvm/MC/MCStreamer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymbol-h">llvm/MC/MCSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetloweringobjectfile-h">llvm/Target/TargetLoweringObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizer-h">llvm/Transforms/Instrumentation/AddressSanitizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/addresssanitizercommon-h">llvm/Transforms/Instrumentation/AddressSanitizerCommon.h</a>"
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86mcinstlower-cpp-">anonymous{X86MCInstLower.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower">X86MCInstLower</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower">X86MCInstLower</a> - This class is used to lower an <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> into an <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a>. <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/noautopaddingscope">NoAutoPaddingScope</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A RAII helper which defines a region of instructions which can't have padding added between them for correctness. <a href="/web-llvm/docs/api/structs/noautopaddingscope/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9aff66ab49598cc0f305402e153f36">emitX86Nops</a> (MCStreamer &amp;OS, unsigned NumBytes, const X86Subtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the optimal amount of multi-byte nops on <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>. <a href="#a0f9aff66ab49598cc0f305402e153f36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c971705a49e1964c2ce26c6a537650">getRetOpcode</a> (const X86Subtarget &amp;Subtarget)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3f0f12dd242748fc4c62997ae5b6b0">convertTailJumpOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab371721ad31c3a0d4e5eb8fce0e8a13a">emitNop</a> (MCStreamer &amp;OS, unsigned NumBytes, const X86Subtarget *Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the largest nop instruction smaller than or equal to <span class="doxyComputerOutput">NumBytes</span> bytes. <a href="#ab371721ad31c3a0d4e5eb8fce0e8a13a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2523bc34268ccc01e29d2b27c55cd9">PrevCrossBBInst</a> (MachineBasicBlock::const_iterator MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a> (const MachineInstr *MI, unsigned SrcIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a> (raw_ostream &amp;CS, const MachineInstr *MI, unsigned SrcOpIdx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a096c73ed00d089d8655ad2da3963380c">printShuffleMask</a> (raw_ostream &amp;CS, StringRef Src1Name, StringRef Src2Name, ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a> (const MachineInstr *MI, unsigned SrcOp1Idx, unsigned SrcOp2Idx, ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a> (const APInt &amp;Val, raw_ostream &amp;CS, bool PrintZero=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae942149adacb516624bfb499d4d627">printConstant</a> (const APFloat &amp;Flt, raw_ostream &amp;CS, bool PrintZero=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a> (const Constant *COp, unsigned BitWidth, raw_ostream &amp;CS, bool PrintZero=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a> (const MachineInstr *MI, MCStreamer &amp;OutStreamer, int SclWidth, int VecWidth, const char *ShuffleComment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd11f377f141eaca592b06fff653370">printBroadcast</a> (const MachineInstr *MI, MCStreamer &amp;OutStreamer, int Repeats, int BitWidth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60061d374eb7273d11025f881472a4d8">printExtend</a> (const MachineInstr *MI, MCStreamer &amp;OutStreamer, int SrcEltBits, int DstEltBits, bool IsSext)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db2fa81479108c5c22590464d2cc2ce">printSignExtend</a> (const MachineInstr *MI, MCStreamer &amp;OutStreamer, int SrcEltBits, int DstEltBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a> (const MachineInstr *MI, MCStreamer &amp;OutStreamer, int SrcEltBits, int DstEltBits)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a> (const MachineInstr *MI, MCStreamer &amp;OutStreamer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc048365e155399ad72421f8af95ccd7">EnableBranchHint</a>("enable-branch-hint", cl::desc("Enable branch hint."), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6c4b32ad3a553b6ef72eb7f2114b1bf">BranchHintProbabilityThreshold</a>("branch-hint-probability-threshold", cl::desc("The probability threshold of enabling branch hint."), cl::init(50), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(Prefix, Instr, Suffix, Postfix)&nbsp;&nbsp;&nbsp;  case X86::Prefix##Instr##Suffix##rm##Postfix:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7038b112bce8c287ca922b9db0907d4d">CASE_ARITH_RM</a>(Instr)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f4e391f884a64e1dbe988ad2801eb91">MASK_AVX512_CASE</a>(Instr)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3512c6de6d5c88504bba888e72206fd6">MOV_CASE</a>(Prefix, Suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Suffix, Postfix)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee29f183e9b452dd1f3cddb2b33868b">CASE_128_MOV_RM</a>()&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86584f6fd152df21da090335af28a96f">CASE_256_MOV_RM</a>()&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ad20091c4dd5a2f03031e207b8ffc2">CASE_512_MOV_RM</a>()&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(Prefix, Ext, Type, Suffix, Postfix)&nbsp;&nbsp;&nbsp;  case X86::Prefix##PMOV##Ext##Type##Suffix##rm##Postfix:</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac210ccb9d4213e4a34acfc098aa16d36">CASE_MOVX_RM</a>(Ext, Type)&nbsp;&nbsp;&nbsp;...</td>
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

### addConstantComments() {#a72515d2f0a6b48c9949ac83674b46a89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addConstantComments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer)</td>
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



<p>Definition at line 1783 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691">llvm::X86::AddrNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#afee29f183e9b452dd1f3cddb2b33868b">CASE_128_MOV_RM</a>, <a href="#a86584f6fd152df21da090335af28a96f">CASE_256_MOV_RM</a>, <a href="#af6ad20091c4dd5a2f03031e207b8ffc2">CASE_512_MOV_RM</a>, <a href="#a7038b112bce8c287ca922b9db0907d4d">CASE_ARITH_RM</a>, <a href="#ac210ccb9d4213e4a34acfc098aa16d36">CASE_MOVX_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb680fe35fd4d397b7d0674c45861008">llvm::DecodePSHUFBMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5fb0db87ada1b48888e070c009007845">llvm::DecodeVPERMIL2PMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed1906d1fc3026d1bf29313dfcfa68">llvm::DecodeVPERMILPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2ea0deda81eb9adf593b817b901fc1e">llvm::DecodeVPPERMMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/dstop/#ad5f891a5d9822c7aab1b8bb0190a522f">llvm::DstOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a124a43d72f8680a64fdd7132d29b1775">llvm::X86ATTInstPrinter::getRegisterName</a>, <a href="#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a>, <a href="#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af9123ce22c3cada196c14e31be149c6e">llvm::X86::getVectorRegisterWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a6f4e391f884a64e1dbe988ad2801eb91">MASK_AVX512_CASE</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="#a1db2fa81479108c5c22590464d2cc2ce">printSignExtend</a>, <a href="#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a>, <a href="#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### convertTailJumpOpcode() {#a4f3f0f12dd242748fc4c62997ae5b6b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned convertTailJumpOpcode (unsigned Opcode)</td>
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



<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### emitNop() {#ab371721ad31c3a0d4e5eb8fce0e8a13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned emitNop (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, unsigned NumBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> * Subtarget)</td>
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

<p>Emit the largest nop instruction smaller than or equal to <span class="doxyComputerOutput">NumBytes</span> bytes.</p>


<p>Return the size of nop emitted.</p>


<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#af94e84eca402017c9ce57b7b4c4104e3">llvm::MCStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">llvm::MCStreamer::emitInstruction</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0f9aff66ab49598cc0f305402e153f36">emitX86Nops</a>.</p>

</div>
</div>

### emitX86Nops() {#a0f9aff66ab49598cc0f305402e153f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitX86Nops (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS, unsigned NumBytes, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> * Subtarget)</td>
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

<p>Emit the optimal amount of multi-byte nops on <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a>.</p>

<p>Definition at line 776 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab371721ad31c3a0d4e5eb8fce0e8a13a">emitNop</a>.</p>

</div>
</div>

### getRetOpcode() {#a16c971705a49e1964c2ce26c6a537650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getRetOpcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; Subtarget)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### getShuffleComment() {#aef7abd9e585da4743700d2c04b17ab77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getShuffleComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned SrcOp1Idx, unsigned SrcOp2Idx, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
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



<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a124a43d72f8680a64fdd7132d29b1775">llvm::X86ATTInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a> and <a href="#a096c73ed00d089d8655ad2da3963380c">printShuffleMask</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### getSrcIdx() {#a5272a0a447e8c15711a3b35d7b0d90a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getSrcIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned SrcIdx)</td>
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



<p>Definition at line 1451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ac5feea989366c35ad4b85148a305f116">llvm::X86II::isKMasked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a07b28b4355ad8daca32f6087453982a0">llvm::X86II::isKMergeMasked</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a> and <a href="#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a>.</p>

</div>
</div>

### PrevCrossBBInst() {#aad2523bc34268ccc01e29d2b27c55cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::const_iterator PrevCrossBBInst (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a199a6e4bfdffc8f3379ef4f35004488f">MachineBasicBlock::const_iterator</a> MBBI)</td>
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



<p>Definition at line 1439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### printBroadcast() {#a5bd11f377f141eaca592b06fff653370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printBroadcast (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, int Repeats, int BitWidth)</td>
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



<p>Definition at line 1635 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### printConstant() {#ade5b1fe412812c4f0d9bb11e2cf2f4d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Val, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CS, bool PrintZero=false)</td>
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



<p>Definition at line 1542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5fa938f247b20cccc87cc8a6e5d20aa6">llvm::APInt::getNumWords</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ada7af1de63a848b2f452d63958de39fe">llvm::APInt::getRawData</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="#a95f58fa5cb1c9a72e5ea815a5036a2e4">printConstant</a>, <a href="#a60061d374eb7273d11025f881472a4d8">printExtend</a> and <a href="#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a>.</p>

</div>
</div>

### printConstant() {#a1ae942149adacb516624bfb499d4d627}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; Flt, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CS, bool PrintZero=false)</td>
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



<p>Definition at line 1558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11534cddb9d36ce7b049eefacc295a96">Flt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a> and <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a416dc650964ad640df99464a32aa49da">llvm::APFloat::toString</a>.</p>

</div>
</div>

### printConstant() {#a95f58fa5cb1c9a72e5ea815a5036a2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printConstant (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * COp, unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CS, bool PrintZero=false)</td>
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



<p>Definition at line 1569 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a833daf718a49c5cd637d8c9ddeaebe07">llvm::Type::getPrimitiveSizeInBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#aa0fd6bf3d33236279db7b707bba755f4">llvm::Type::isDoubleTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3ffc75c3a4cb82ba307a3334483eb4ac">llvm::Type::isFloatTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a8cf1f36cc41c466e66d6467e40554841">llvm::Type::isHalfTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a> and <a href="#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>.</p>

</div>
</div>

### printDstRegisterName() {#abadd3db62d81d4ecaa7630291dc36573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printDstRegisterName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, unsigned SrcOpIdx)</td>
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



<p>Definition at line 1463 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dstop/#ad5f891a5d9822c7aab1b8bb0190a522f">llvm::DstOp::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86attinstprinter/#a124a43d72f8680a64fdd7132d29b1775">llvm::X86ATTInstPrinter::getRegisterName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ac5feea989366c35ad4b85148a305f116">llvm::X86II::isKMasked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a07b28b4355ad8daca32f6087453982a0">llvm::X86II::isKMergeMasked</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a>, <a href="#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a> and <a href="#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a>.</p>

</div>
</div>

### printExtend() {#a60061d374eb7273d11025f881472a4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, int SrcEltBits, int DstEltBits, bool IsSext)</td>
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



<p>Definition at line 1653 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#a1dc76cc8bf703e6ada68bededcbb9573">llvm::APInt::zext</a>.</p>


<p>Referenced by <a href="#a1db2fa81479108c5c22590464d2cc2ce">printSignExtend</a> and <a href="#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a>.</p>

</div>
</div>

### printShuffleMask() {#a096c73ed00d089d8655ad2da3963380c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; CS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Src1Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Src2Name, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
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



<p>Definition at line 1481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689a3f112d168d45b1ab58a80c2b9f7e6cb4">llvm::SM_SentinelUndef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#afaddf811d44f58e7d0e16ca3266b8689ac131901c70cd3380fd61a47415b58740">llvm::SM_SentinelZero</a>.</p>


<p>Referenced by <a href="#aef7abd9e585da4743700d2c04b17ab77">getShuffleComment</a> and <a href="#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a>.</p>

</div>
</div>

### printSignExtend() {#a1db2fa81479108c5c22590464d2cc2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printSignExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, int SrcEltBits, int DstEltBits)</td>
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



<p>Definition at line 1682 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a60061d374eb7273d11025f881472a4d8">printExtend</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### printZeroExtend() {#adf508d7280c5a6d9fb7d0e2cf2f426c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printZeroExtend (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, int SrcEltBits, int DstEltBits)</td>
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



<p>Definition at line 1686 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01ddb8ea0c52fea9a3e87e46a10d00d8">llvm::DecodeZeroExtendMask</a>, <a href="#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af9123ce22c3cada196c14e31be149c6e">llvm::X86::getVectorRegisterWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a>, <a href="#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="#a096c73ed00d089d8655ad2da3963380c">printShuffleMask</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### printZeroUpperMove() {#a6132fb3423ce0d8846f93102d9658bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printZeroUpperMove (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OutStreamer, int SclWidth, int VecWidth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ShuffleComment)</td>
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



<p>Definition at line 1608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab7d20e7a4f79f39c97b3329389c8db88">llvm::X86::getConstantFromPool</a>, <a href="#a5272a0a447e8c15711a3b35d7b0d90a9">getSrcIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#ade5b1fe412812c4f0d9bb11e2cf2f4d3">printConstant</a>, <a href="#abadd3db62d81d4ecaa7630291dc36573">printDstRegisterName</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BranchHintProbabilityThreshold {#af6c4b32ad3a553b6ef72eb7f2114b1bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; BranchHintProbabilityThreshold("branch-hint-probability-threshold", cl::desc("The probability threshold of enabling branch hint."), cl::init(50), cl::Hidden)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86asmprinter/#a1959523b897eac43ed99525fd9849be1">llvm::X86AsmPrinter::emitInstruction</a>.</p>

</div>
</div>

### EnableBranchHint {#adc048365e155399ad72421f8af95ccd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableBranchHint("enable-branch-hint", cl::desc("Enable branch hint."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### CASE\_128\_MOV\_RM {#afee29f183e9b452dd1f3cddb2b33868b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_128_MOV_RM()&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a3512c6de6d5c88504bba888e72206fd6">MOV_CASE</a>(, )   /* SSE */                                                     \
  <a href="#a3512c6de6d5c88504bba888e72206fd6">MOV_CASE</a>(V, )  /* <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a0f2500907bbad2fb795fba8fafd31b2a">AVX</a>-128 */                                                 \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z128, )                                                      \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z128, k)                                                     \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z128, kz)
</div>
</dd>
</dl>

<p>Definition at line 2019 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### CASE\_256\_MOV\_RM {#a86584f6fd152df21da090335af28a96f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_256_MOV_RM()&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a3512c6de6d5c88504bba888e72206fd6">MOV_CASE</a>(V, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>) /* <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a0f2500907bbad2fb795fba8fafd31b2a">AVX</a>-256 */                                                 \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z256, )                                                      \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z256, k)                                                     \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z256, kz)                                                    \
</div>
</dd>
</dl>

<p>Definition at line 2026 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### CASE\_512\_MOV\_RM {#af6ad20091c4dd5a2f03031e207b8ffc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_512_MOV_RM()&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z, )                                                         \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z, k)                                                        \
  <a href="#abe3b6c10aa992f57d166d4702d458a4e">MOV_AVX512_CASE</a>(Z, kz)                                                       \
</div>
</dd>
</dl>

<p>Definition at line 2032 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### CASE\_ARITH\_RM {#a7038b112bce8c287ca922b9db0907d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_ARITH_RM(Instr)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(, Instr, , )   /* SSE */                                          \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, , )  /* <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a0f2500907bbad2fb795fba8fafd31b2a">AVX</a>-128 */                                      \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, ) /* <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-dispatch-c/#a6efa629275df21393eef82e3bf972460a0f2500907bbad2fb795fba8fafd31b2a">AVX</a>-256 */                                      \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z128, )                                                 \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z128, k)                                                \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z128, kz)                                               \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z256, )                                                 \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z256, k)                                                \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z256, kz)                                               \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z, )                                                    \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z, k)                                                   \
  <a href="#a6e82720dbb99a9820cd6923e54bc1cc6">INSTR_CASE</a>(V, Instr, Z, kz)
</div>
</dd>
</dl>

<p>Definition at line 1911 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### CASE\_MOVX\_RM {#ac210ccb9d4213e4a34acfc098aa16d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_MOVX_RM(Ext, Type)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(, Ext, Type, , )                                                   \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, , )                                                  \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>, )                                                 \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z128, )                                              \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z128, k )                                            \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z128, kz )                                           \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z256, )                                              \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z256, k )                                            \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z256, kz )                                           \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z, )                                                 \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z, k )                                               \
  <a href="#ac6622a3ec1786ff30a69675c680784fb">MOVX_CASE</a>(V, Ext, Type, Z, kz )
</div>
</dd>
</dl>

<p>Definition at line 2130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### INSTR\_CASE {#a6e82720dbb99a9820cd6923e54bc1cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTR_CASE(Prefix, Instr, Suffix, Postfix)&nbsp;&nbsp;&nbsp;  case X86::Prefix##Instr##Suffix##rm##Postfix:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1908 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### MASK\_AVX512\_CASE {#a6f4e391f884a64e1dbe988ad2801eb91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MASK_AVX512_CASE(Instr)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Instr:                                                                  \
  case Instr##k:                                                               \
  case Instr##kz:
</div>
</dd>
</dl>

<p>Definition at line 1964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>


<p>Referenced by <a href="#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>.</p>

</div>
</div>

### MOV\_AVX512\_CASE {#abe3b6c10aa992f57d166d4702d458a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MOV_AVX512_CASE(Suffix, Postfix)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case X86::VMOVDQA64##Suffix##rm##Postfix:                                    \
  case X86::VMOVDQA32##Suffix##rm##Postfix:                                    \
  case X86::VMOVDQU64##Suffix##rm##Postfix:                                    \
  case X86::VMOVDQU32##Suffix##rm##Postfix:                                    \
  case X86::VMOVDQU16##Suffix##rm##Postfix:                                    \
  case X86::VMOVDQU8##Suffix##rm##Postfix:                                     \
  case X86::VMOVAPS##Suffix##rm##Postfix:                                      \
  case X86::VMOVAPD##Suffix##rm##Postfix:                                      \
  case X86::VMOVUPS##Suffix##rm##Postfix:                                      \
  case X86::VMOVUPD##Suffix##rm##Postfix:
</div>
</dd>
</dl>

<p>Definition at line 2007 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### MOV\_CASE {#a3512c6de6d5c88504bba888e72206fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MOV_CASE(Prefix, Suffix)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case X86::Prefix##MOVAPD##Suffix##rm:                                        \
  case X86::Prefix##MOVAPS##Suffix##rm:                                        \
  case X86::Prefix##MOVUPD##Suffix##rm:                                        \
  case X86::Prefix##MOVUPS##Suffix##rm:                                        \
  case X86::Prefix##MOVDQA##Suffix##rm:                                        \
  case X86::Prefix##MOVDQU##Suffix##rm:
</div>
</dd>
</dl>

<p>Definition at line 1999 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

### MOVX\_CASE {#ac6622a3ec1786ff30a69675c680784fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MOVX_CASE(Prefix, Ext, Type, Suffix, Postfix)&nbsp;&nbsp;&nbsp;  case X86::Prefix##PMOV##Ext##Type##Suffix##rm##Postfix:</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp">X86MCInstLower.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
