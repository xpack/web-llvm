---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `HexagonBitTracker.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-h">HexagonBitTracker.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-h">HexagonInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonregisterinfo-h">HexagonRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsubtarget-h">HexagonSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;cstdlib&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-hexagonbittracker-cpp-">anonymous{HexagonBitTracker.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagonbittracker-cpp-/registerrefs">RegisterRefs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ee73ba17c3a2cb54752905e99d77357">op</a>(i)&nbsp;&nbsp;&nbsp;MI.getOperand(i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1b5bd9424a1d1082d4bd670b1a0be6">rc</a>(i)&nbsp;&nbsp;&nbsp;RegisterCell::ref(getCell(<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>[i], Inputs))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2239343bf72ef6a991165363ac0386c3">im</a>(i)&nbsp;&nbsp;&nbsp;MI.getOperand(i).getImm()</td>
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

## Macro Definitions

### im {#a2239343bf72ef6a991165363ac0386c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define im(i)&nbsp;&nbsp;&nbsp;MI.getOperand(i).getImm()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#acf8f1219dc8b656e8e11c4b08edc8979">llvm::AArch64TargetLowering::AArch64TargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa782c58995f9a6e00cf5a8500a9a8508">llvm::ARMTargetLowering::ARMTargetLowering</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instrbuilder/#a54e306500b1968dcb5c02cb0570675bf">llvm::mca::InstrBuilder::InstrBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a190dd3c890042807e4008b5bdd04927a">llvm::RISCVTargetLowering::RISCVTargetLowering</a>.</p>

</div>
</div>

### op {#a0ee73ba17c3a2cb54752905e99d77357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define op(i)&nbsp;&nbsp;&nbsp;MI.getOperand(i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a6cdddfff71264f7e1e744fdea34085d3">llvm::ARMTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#aae14937e233b1d930d6f040de852ff30">llvm::MipsInstrInfo::adjustStackPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a99424675c5fc439756409a02a8f9405a">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ae65337bd76ece9e7b1d20cf665bfa742">llvm::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#ad2e0ab6d7096fe67a2216fe349044387">llvm::CastInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ade174bb0481f851b34f77b9f83c5b7ae">DecodeTBLInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a78802c522ed764cedc1bafcf628dd154">DecodeVCVTD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9e5902642b306bad7e557cc0030a8c3b">DecodeVCVTQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a42f8fec9a1fa9d471abf77a8eead0da1">doemit</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#ab437a1156833e5395a0102102cf93c6f">doinsert</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcmccodeemitter-cpp-/sparcmccodeemitter/#a9887c70467f820ed639080a7edcdabaa">anonymous{SparcMCCodeEmitter.cpp}::SparcMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumcexpr/#ac7ea2a3563181056354939fd2ed18e7e">llvm::AMDGPUMCExpr::evaluateAsRelocatableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a091a19fb76439b9fff59f052e2648ee9">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleSignedRelationalComparison</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#acda7f859f08095376f8e49522a5d21b6">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::hasDivergentDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-armlatencymutations-cpp-/instructioninformation/#a6b97b7ecbffbfda703ccfe7e14d4d0c3">llvm::anonymous{ARMLatencyMutations.cpp}::InstructionInformation::InstructionInformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#afd44ea11a1de5d05327fb0ef9d20177f">IsRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a7a043e6726bd97f9874d70905025648b">llvm::ARM::isVpred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abcc5d81435bd0105c84f84f1c072994a">llvm::ARM::isVpred</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreinstrinfo-cpp/#af382210044ec5f261709190eb6e096bc">isZeroImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a5e5faf569e1b9d35ccd98046c7ad6d61">llvm::MipsInstrInfo::isZeroImm</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga1fdcd0e733e587b2d5e7a49f7b903ceb">LLVM_ATTRIBUTE_C_DEPRECATED</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga04f176726bc121e9a42d337ead9113a7">LLVMBuildAtomicRMW</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga95b63494bb29b3ae92199c911b659620">LLVMBuildAtomicRMWSyncScope</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#a7357d4d98f9741b2ede9180f437f7623">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::markDefsDivergent</a>, <a href="/web-llvm/docs/api/structs/llvm/physregsuoper/#aede5b97ee71acf0e3d68847f2a433039">llvm::PhysRegSUOper::PhysRegSUOper</a>, <a href="/web-llvm/docs/api/classes/llvm/arminstprinter/#af16346148e47bd920deff1ae577e52fc">llvm::ARMInstPrinter::printAM3PreOrOffsetIndexOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVSignExtendExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevtruncateexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVTruncateExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVZeroExtendExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#acb400ab122ec2c7e1222c7dc7eac079e">llvm::SCEVCastExpr::SCEVCastExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevintegralcastexpr/#a8da5e068d45d31d39f6f449efd8d1d9e">llvm::SCEVIntegralCastExpr::SCEVIntegralCastExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/use-iterator/#a3de0b67859696f5bb9e0cc64b2178101">llvm::SDNode::use_iterator::SDNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/user-iterator/#a3de0b67859696f5bb9e0cc64b2178101">llvm::SDNode::user_iterator::SDNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#aa0b3de3815c7ba67bd6b19ef08ac9f1c">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1a45bf6d0fbef0afa6304a0a90d4cc7c">SpecialAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#a52f192b099a610d4a5c4b203bd9b46bb">llvm::anonymous{SPIRVStructurizer.cpp}::visit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#a090736355958192cac4db32336c48bbd">visit</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpostlegalizer-cpp/#ab4bdcedb642aa6612156bcc2ac0a0d7b">visit</a>.</p>

</div>
</div>

### rc {#a2e1b5bd9424a1d1082d4bd670b1a0be6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rc(i)&nbsp;&nbsp;&nbsp;RegisterCell::ref(getCell(<a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>[i], Inputs))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbittracker-cpp">HexagonBitTracker.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a49b4d08c8b0024b97c7e090a0b3e50f6">llvm::HexagonEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/rpmalloc/rpmalloc-c/#a2ae01990651a75a352409fb1fbf85d05">rpmalloc_initialize_config</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
