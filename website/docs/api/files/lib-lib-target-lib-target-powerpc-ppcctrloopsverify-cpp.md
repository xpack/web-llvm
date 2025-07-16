---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PPCCTRLoopsVerify.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-h">MCTargetDesc/PPCMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppc-h">PPC.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallset-h">llvm/ADT/SmallSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/ilist-iterator-h">llvm/ADT/ilist_iterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundleiterator-h">llvm/CodeGen/MachineInstrBundleIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/register-h">llvm/CodeGen/Register.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/passregistry-h">llvm/PassRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/printable-h">llvm/Support/Printable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-ppcctrloopsverify-cpp-">anonymous{PPCCTRLoopsVerify.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-ppcctrloopsverify-cpp-/ppcctrloopsverify">PPCCTRLoopsVerify</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae138719f744d370b3dabf2d8588ae069">INITIALIZE_PASS_BEGIN</a> (PPCCTRLoopsVerify, "ppc-ctr-loops-verify", "PowerPC CTR Loops Verify", false, false) INITIALIZE_PASS_END(PPCCTRLoopsVerify</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a900f0d22e87168edb0dcb0f4d0187cb8">clobbersCTR</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a302583dfd143c9bb87f8274ba0dc727b">verifyCTRBranch</a> (MachineBasicBlock *MBB, MachineBasicBlock::iterator I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ppc ctr <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593cc2f204f7b2edc16ee222c37c3196">verify</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ppc ctr <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a> PowerPC CTR <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ppc ctr <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a> PowerPC CTR <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82285e9120a81e33c01792e5021d555c">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"ppc-ctrloops-verify"</td>
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

### clobbersCTR() {#a900f0d22e87168edb0dcb0f4d0187cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool clobbersCTR (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a302583dfd143c9bb87f8274ba0dc727b">verifyCTRBranch</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#ae138719f744d370b3dabf2d8588ae069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (PPCCTRLoopsVerify, "ppc-ctr-<a href="/web-llvm/docs/api/files/lib/lib/analysis/loopinfo-cpp/#a49ae40a9c91d665793aaed656c26ca30">loops</a>-verify", "PowerPC CTR <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a> Verify", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### verifyCTRBranch() {#a302583dfd143c9bb87f8274ba0dc727b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool verifyCTRBranch (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> I)</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="#a900f0d22e87168edb0dcb0f4d0187cb8">clobbersCTR</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-ppcctrloopsverify-cpp-/ppcctrloopsverify/#a77d7469acf0eff421a41b7f991ea5724">anonymous{PPCCTRLoopsVerify.cpp}::PPCCTRLoopsVerify::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### false {#a82285e9120a81e33c01792e5021d555c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ppc ctr loops PowerPC CTR Loops false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>

</div>
</div>

### verify {#a593cc2f204f7b2edc16ee222c37c3196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ppc ctr loops verify</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64legalizerinfo/#ae27667d7c3fbd41b18fd5838fc4f0553">llvm::AArch64LegalizerInfo::AArch64LegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a8c46e5a35a9df5b131a85976d8d70af0">llvm::AArch64RegisterBankInfo::AArch64RegisterBankInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a44a4d4c034685aa34a4e8f62b0976e6c">llvm::AMDGPULegalizerInfo::AMDGPULegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armlegalizerinfo/#a0c94d0f4f62bd71d26a8020faf70b9f0">llvm::ARMLegalizerInfo::ARMLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#aa6bd85a0e2d2b53c2f59708830ba3c6b">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::end</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#af247a28fd83cea9873d310162110439f">llvm::IRPosition::IRPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/mipslegalizerinfo/#a63e981ba0042fbfdd3857f66c82d8d28">llvm::MipsLegalizerInfo::MipsLegalizerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a48dd43ef05b66261790497edbdac92d9">llvm::JumpThreadingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolutionverifierpass/#a922e2e00f7528f19fdece7de80099fc2">llvm::ScalarEvolutionVerifierPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-armconstantislandpass-cpp-/armconstantislands/#aaf4297850ccff6052205f45bc2ba2f87">anonymous{ARMConstantIslandPass.cpp}::ARMConstantIslands::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-branchrelaxation-cpp-/branchrelaxation/#afa14354480232f315ca52b78b7b782bd">anonymous{BranchRelaxation.cpp}::BranchRelaxation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfiinstrinserter-cpp-/cfiinstrinserter/#abb6123b2fb2967969ac1a43ffe98d0d5">anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/x86legalizerinfo/#abfc562c1c7aebc23222627fa24d11df5">llvm::X86LegalizerInfo::X86LegalizerInfo</a>.</p>

</div>
</div>

### Verify {#a345bd69760b9ee32b3f49d4fc04120fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">static void Verify</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#ae4433b84f2a85686e6ec21134626dab0">llvm::TargetPassConfig::addVerifyPass</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#a491288b9b4b16c83d513619f00fdcc6c">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantint/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::ConstantInt::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::NoCFIValue::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#a8014de6610ee432b675e3819e011acb2">llvm::sandboxir::User::getOperandUseDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#afbda7524d17168713343950a44657d70">llvm::sandboxir::Constant::getOperandUseInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a212c05932ca0d1ac0e87b008542aeaa9">llvm::sandboxir::GlobalObject::getOperandUseInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user/#aa469c4f23b78900ac9135b3417819f31">llvm::sandboxir::User::getOperandUseInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable/#a553e49a319c70887144ab0be1fedffad">llvm::GVNPass::ValueTable::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnpass/valuetable/#a5b8ab87af8cabbd0686f6e2e5c3a13ae">llvm::GVNPass::ValueTable::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/safepointirverifierpass/#af94bb71714afbf2f143e6535c8264e56">llvm::SafepointIRVerifierPass::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-safepointirverifier-cpp-/safepointirverifier/#abd707c03eccdccbcdbb0c4844bd66852">anonymous{SafepointIRVerifier.cpp}::SafepointIRVerifier::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#a4511f5243766afa68114a68c157c51dd">llvm::dwarf_linker::classic::DWARFLinker::setVerifyInputDWARF</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a7e83aaae6734ba1c6b88cf33c1385433">llvm::dwarf_linker::DWARFLinkerBase::setVerifyInputDWARF</a>, <a href="/web-llvm/docs/api/groups/methods/#ga8729af41da30f5c338b8978beacc95b1">llvm::dwarf_linker::parallel::DWARFLinkerImpl::setVerifyInputDWARF</a>, <a href="/web-llvm/docs/api/classes/llvm/enginebuilder/#a892d551cc875d9149c447f10caea9656">llvm::EngineBuilder::setVerifyModules</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a05f6219fb693e81805662dd4bb42e6e9">llvm::ExecutionEngine::setVerifyModules</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"ppc-ctrloops-verify"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp">PPCCTRLoopsVerify.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
