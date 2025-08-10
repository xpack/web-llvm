---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/sandboxir/value-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Value.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-h">LLVMContextImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/deriveduser-h">llvm/IR/DerivedUser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/typedpointertype-h">llvm/IR/TypedPointerType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include "llvm/IR/Value.def"
#include "llvm/IR/Instruction.def"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/value-h">llvm/SandboxIR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/context-h">llvm/SandboxIR/Context.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">llvm/SandboxIR/User.h</a>"
#include &lt;sstream&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-value-cpp-">anonymous{Value.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/sandboxir">sandboxir</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54c5d2418d4f9f343034e5139b509fbc">checkType</a> (Type *Ty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912e3fffa4865ae00253b61517516e50">isUnDroppableUser</a> (const User *U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c3c0815d6e4c2535bc27f822f5e0960">getSymTab</a> (Value *V, ValueSymbolTable *&amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34433c37334a1cde3d58cde3099257dd">contains</a> (SmallPtrSetImpl&lt; ConstantExpr * &gt; &amp;Cache, ConstantExpr *Expr, Constant *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab338bbeb1b837153bb97d7aad7f4dc68">contains</a> (Value *Expr, Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892500981aa7cebf6ad1a8a06f9e852e">replaceDbgUsesOutsideBlock</a> (Value *V, Value *New, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace llvm.dbg. <a href="#a892500981aa7cebf6ad1a8a06f9e852e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1874ee4114fb76d9b4772ea6c0daa760">getOffsetFromIndex</a> (const GEPOperator *GEP, unsigned Idx, const DataLayout &amp;DL)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4025923692762bfb9a69935f9c10aeb6">UseDerefAtPointSemantics</a>("use-dereferenceable-at-point-semantics", cl::Hidden, cl::init(false), cl::desc("Deref attributes and metadata infer facts at definition only"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d80d7a17dae775c0b19c64d8c5e0495">HANDLE_VALUE</a>(Name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a599351901c1999079b9144b449bbd366">HANDLE_MEMORY_VALUE</a>(Name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf38b15c88cc9aaa1d9d16d8ef901eef">HANDLE_CONSTANT</a>(Name)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8827f21a62bce86aa16372160a0c1a4e">HANDLE_INSTRUCTION</a>(Name)&nbsp;&nbsp;&nbsp;/* nothing */</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ddf810a37aa06799899d388fdb6bfb">HANDLE_INST</a>(N, OPC, CLASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbebec61a87f66d24bd85056778ae42c">HANDLE_USER_INST</a>(N, OPC, CLASS)</td>
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

### checkType() {#a54c5d2418d4f9f343034e5139b509fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * checkType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file Value.cpp, definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### contains() {#a34433c37334a1cde3d58cde3099257dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool contains (<a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> * &gt; &amp; Cache, <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
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



<p>Declaration at line 469 of file Value.cpp, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac4f56500894c6c3ca92c54b569cc42a7">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR32as64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ac45d96b1d1611280239c5f5ec90e1d22">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addGPR64as32Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a25127edbfd500680786a7964074d8629">llvm::X86Operand::addGR16orGR32orGR64Operands</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a86467b8eb24fee4d7a713a537685d783">llvm::X86Operand::addGR32orGR64Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a69eda91bc353715ea7d51bc6d0d2e849">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg128Operands</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#a1b12b775c6f9e800fb7fd722fd6a5e90">anonymous{AArch64AsmParser.cpp}::AArch64Operand::addVectorReg64Operands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#ace3b0eb52be3988997a7f6e4a5b59aab">llvm::PPCFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a4554341b316dd0b06a915ec883f4f74a">llvm::SystemZELFFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7c6fdca5f3b44d406ff07e43b2f140f6">llvm::X86FrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aec0904aef5bec338f4fea047c49455aa">llvm::ARMBaseInstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad8756402b6bd331b493dc7c0b3efd984">llvm::X86InstrInfo::breakPartialRegDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#ad9c4463170797dc633ce8dfa192f132b">llvm::X86InstrInfo::buildClearRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a78b51fef75563bb7e8f5398de1593396">canSpillOnFrameIndexAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#ab1225687dc25ba807ce6784cac23d9f5">CheckBaseRegAndIndexRegAndScale</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a7ad01245fba0cda069bb7ce68a9296a4">llvm::IRSimilarity::IRSimilarityCandidate::compareAssignmentMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#a898b67642540caffd623ae7b0caf2281">llvm::BaseIndexOffset::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a93378da7b054ace293c4598f52e7d3d2">llvm::RegionBase&lt; Tr &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ade00a4708e793e75a00a3030325cbf84">llvm::AArch64InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/arcinstrinfo/#a741b52aa71d8a88aed13b09b7b6183cb">llvm::ARCInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abef9f720617461778f1a2e49d17ea159">llvm::ARMBaseInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/avrinstrinfo/#a5bde594eff371b34c5f5bf6222b690f6">llvm::AVRInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfinstrinfo/#ac0442b8f7343b837eae4c4a0db532cf8">llvm::BPFInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyinstrinfo/#ae8be35955783557ba6a8d97bcf8353e7">llvm::CSKYInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ac6fc9913b21716cfbd41b6616e8aef4d">llvm::HexagonInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a75c1ba5e07585f5eafbd2a56ba489b5e">llvm::LanaiInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchinstrinfo/#a759a3354d37a7d694ba126ace98547f0">llvm::LoongArchInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo/#a782862328ea598dcc50374eb9086d36b">llvm::M68kInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16instrinfo/#a851cd4eaa854ab481ba59f5eb9163b8f">llvm::Mips16InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#a28dc5e4998fe0b9c82c9a30f9c20ca08">llvm::MipsSEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430instrinfo/#aa33d04c71419c4cd5825c3cedeee8f4c">llvm::MSP430InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a3e0a4dad177be52a38a07e782fc9207f">llvm::PPCInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#ae780082016f8641ba5a18009b135d01e">llvm::R600InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a5e29efc37d9738b891d35308524d7d5b">llvm::RISCVInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a519410003771768aef013bd57efa6cf4">llvm::SIInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcinstrinfo/#a9cb1dd3dd16025fc64f52adb12c9ce5f">llvm::SparcInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#afbb3d2344086d40fa845201e37538d85">llvm::SystemZInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a3f2267000e9691f1bd4584f4eb4e0cc4">llvm::Thumb1InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb2instrinfo/#a4d30d32e32d7be938a8b0a0f4dd21418">llvm::Thumb2InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/veinstrinfo/#ad8b8d94aaf80cefc49bc3263f05cd741">llvm::VEInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a79b6327f4d0680e2eb8f28cbe3a2abb9">llvm::X86InstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#a6e1e2c2b2879a6a6c0645e538c989331">llvm::XtensaInstrInfo::copyPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a86c845e0c20ff3050cc964d56125c3f5">CopyToFromAsymmetricReg</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a9846bb2bc5672e7627011260772b8d09">llvm::StringMap&lt; std::nullopt_t, AllocatorTy &gt;::count</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4fc810e861bfd77e299cf0ba678ce6d9">anonymous{ARMAsmParser.cpp}::ARMOperand::CreateRegList</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a40c836e17635ff1fde99148b3a54ce80">llvm::X86InstrInfo::describeLoadedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ab041d0f79187663c0cc7c08cdf8227d0">llvm::AArch64FrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a9eb6f3247260b906218068229b8d5b67">llvm::SystemZELFFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a6e21f6830dcb7fd5e3388ff8d510cb27">llvm::RegionBase&lt; RegionTraits&lt; MachineFunction &gt; &gt;::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/arcregisterinfo/#aaf69a259c2c354f83b367585a37bb14d">llvm::ARCRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#a8fbe3f2774ccaaf41bd80a092a9f73e5">llvm::ThumbRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/xcoreregisterinfo/#a135008911313eaf0a75d1f7a960fe915">llvm::XCoreRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a36db540eb7d0490cab86e4cf12ac9116">emitLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a97c69ea577c9578ecadf9469189438d0">emitStore</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#abe2c3303ec55393902e579d316051289">llvm::ARMBaseInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a7941fd2c7d339dfe155c4327fd95fab0">llvm::PPCInstrInfo::expandPostRAPseudo</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a537788ca2a4d7bbdbfad2ac8e5dfabca">llvm::R600InstrInfo::fitsConstReadLimitations</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a0734a023f800982945eec5cff4e9fb22">llvm::ARMAsmBackendDarwin::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a1c5bfacbaceeadc12099696812305909">llvm::RegionBase&lt; Tr &gt;::getBBNode</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ae51e8df80062a62aa693f01400b1ba74">llvm::HexagonInstrInfo::getCompoundCandidateGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#aa22ae5fa624a5c3d5d22aa3f4538e675">llvm::GenericCycle&lt; ContextT &gt;::getCyclePredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a32b36d5a50c710a1f513d6bff9886fe2">llvm::HexagonInstrInfo::getDuplexCandidateGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#ae5afd077192d75cf02f21fb8899a2e7b">llvm::RegionBase&lt; Tr &gt;::getEnteringBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a9e635b2c582b6500e2c79faf06360ca2">llvm::GenericCycle&lt; ContextT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1d9238c61483c12dce660bae4c8cc2d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#aad953b1e46f8bd2ca82b9cb7285a66a7">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#adf6f53d7652b471c995b7d10f3dd2729">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#ab3909bedb90883a3cf8b51b54c837980">llvm::RegionBase&lt; Tr &gt;::getExitingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a408a62c86ed1c263bb09c6d2b7ec09d2">llvm::GenericCycle&lt; ContextT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a46880fab7a9d5bd439725f2acc59b80d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a2afc539a04a12d833eecbf55239b77cd">llvm::RegionBase&lt; Tr &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#af15b2b0c7e2abba2d3e36989685d800f">llvm::gsym::GsymReader::getFunctionInfoDataForAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#aa974adedc988dcb5c7b9600781bec9f1">getHexagonRegisterPair</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a88575baf2ad9f4cd2e2432e6da4a976b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseframelowering-cpp/#a6e8981d26405bd6e2ab701c98fae6770">getMFHiLoOpc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#a4e27e418474f9d51f09a8b940d476faf">getNextRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armbaseregisterinfo-cpp/#ac2221ad71323cfdfb9d5909e7d1f3775">getPairedGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a51539193cc8ad7ae2884993bbb57ddea">llvm::ARMBaseInstrInfo::getPartialRegUpdateClearance</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#a6825b86f34e17792a882f599423f5485">getRC32</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/gisel/x86instructionselector-cpp/#af17921b5ec93b0789e32ab52c9555111">getRegClassFromGRPhysReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aead7c7f29560bc0cfbfe9959f936b456">getRegImmPairPreventingCompression</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmccodeemitter-cpp-/armmccodeemitter/#abf0dad97f8fcbf302ee8cf6d8647a647">anonymous{ARMMCCodeEmitter.cpp}::ARMMCCodeEmitter::getRegisterListOpValue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ad7d8710804e26a041e428fb0bae67559">llvm::SystemZELFFrameLowering::getRegSpillOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#aedf7b10f87dac6226e785d833b71ca36">llvm::RegionBase&lt; Tr &gt;::getSubRegionNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#acede596c16f946c19dacb339e25ff978">getSVECalleeSaveSlotRange</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae069a12f0a2d2deb69e30b439a91190e">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getUniqueExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a462e59069cb22aa0abd869033bb546fb">llvm::LoopBase&lt; BlockT, LoopT &gt;::getUniqueLatchExitBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#ae7ebc88c9b32b51b749bd5bbcfaa5fb8">llvm::LoopBase&lt; BlockT, LoopT &gt;::hasDedicatedExits</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64slshardening-cpp-/thunksset/#a671ca925709006ec7352344969e09f0a">anonymous{AArch64SLSHardening.cpp}::ThunksSet::indexOfXReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a15bbc2e996b691d46e24ff65c21b046a">indirectCopyToAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmovemerger-cpp/#ae773254afe874b8a24c576bb7fc1dfed">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a23393317cdaeed97903d191dcc6c84f8">llvm::AArch64TargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1dfc6019f3ac9b3b50bfc020a60baf7c">llvm::SITargetLowering::insertCopiesSplitCSR</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmovemerger-cpp-/riscvmovemerge/#ac2bebd1f8090a2e93e2c53c4d206c5bc">anonymous{RISCVMoveMerger.cpp}::RISCVMoveMerge::isCandidateToMergeMVSA01</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a661b945147a53ef2ecf91646a481e67c">isEvenReg</a>, <a href="/web-llvm/docs/api/classes/llvm/errataworkaround/#ac8738858a999b4637a7b240e352fdcbd">llvm::ErrataWorkaround::isFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a2a037132ef2f33daa0522efe92a983ed">llvm::AArch64InstrInfo::isGPRCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#afb76a59133e0abcf11caf9ab31e32ccc">llvm::X86Operand::isGR16orGR32orGR64</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a40ecb25e849b579a4e02f93af13b0be3">llvm::X86Operand::isGR32orGR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#ade9944e1adfb7c602c387d072a76d174">llvm::SystemZ::isHighReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#ad81b99aea193e203aeb95e1c5bdba7f4">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isMatrixRegOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a2c17a8268c0736d291a2bc525584bd90">llvm::X86Operand::isMem512_GR16</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a6de950f79cc96b55dadb92ce88e8c0d3">llvm::X86Operand::isMem512_GR32</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a452acb153ae96fb8bb97ea598d035935">llvm::X86Operand::isMem512_GR64</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a9e75976c163f13909189645c9740e87c">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemNoOffsetT</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a316f94e7bf476318f0426980737e724d">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemNoOffsetT2</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#afed576d5b0b29fa1eef40df791149dcc">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemNoOffsetT2NoSp</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86insertprefetch-cpp-/#a366a833ef18a043b50e7c301e306bf24">anonymous{X86InsertPrefetch.cpp}::IsMemOpCompatibleWithPrefetch</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#ae9d0c9579208cfec42989c24fb150fd2">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemRegQOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a4efc8509d58e64f6d4d541d4aa310be7">anonymous{ARMAsmParser.cpp}::ARMOperand::isMemRegRQOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64operand/#acd7238ce7f28b58aefe19170d4c9f934">anonymous{AArch64AsmParser.cpp}::AArch64Operand::isTypedVectorListMultiple</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a055a6f572aa907eb8f0e2caa9251243e">anonymous{ARMAsmParser.cpp}::ARMOperand::isVecListDPair</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a1973c3a74898b1fce1e6b4af641c7689">anonymous{ARMAsmParser.cpp}::ARMOperand::isVecListDPairAllLanes</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a28683d880114063624c0f5f61f454766">anonymous{ARMAsmParser.cpp}::ARMOperand::isVecListDPairSpaced</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#ab60893542cbdf81bc5ebf40d86b59afb">llvm::X86Operand::isVectorReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#af3b87eccd7dfd84ba438253014223161">lowerRISCVVMachineInstrToMCInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a239d964ac9520cb492a050586bab9d35">mapArgRegToOffsetAIX</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a019cd64618c63f99af8a18d51edd11e6">llvm::RISCVRegisterInfo::needsFrameBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a70fad24fc4701e4e8313b3fea8312c1a">nextReg</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a5dd8beec7af2e26f9b8bb9a7349897a7">llvm::RegionBase&lt; Tr &gt;::outermostLoopInRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aa18f12a3fd9c95854df97891e6d2c338">llvm::RISCVISAInfo::parseArchString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a185f9311cecc76ba862f1420c20db158">printAsmMRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmprinter-cpp-/sparcasmprinter/#a23bf1a3ca7dacaf7d37090cc7816dfe1">anonymous{SparcAsmPrinter.cpp}::SparcAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonasmprinter/#a81e38a8f99bc74ae4acb4d135d1b7278">llvm::HexagonAsmPrinter::PrintAsmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a76421690e64ee4e01b59f44c74fa9c20">printAsmVRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a3178261c88c74264649ee4b881e19306">llvm::ARMAsmPrinter::printOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a2f9c9ef300cdd17a112e9760aaf73e82">llvm::MipsAsmPrinter::printSavedRegsBitmask</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a96feb3493457dc69868b789630e4506b">llvm::AArch64RegisterInfo::regNeedsCFI</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a6799c4d668d7c7dd663b83adcf3667cc">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::removeAccPrimeUnprime</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#abd429aeb9a967ffa720ea42621ee6f2d">llvm::LoopBase&lt; BasicBlock, Loop &gt;::replaceChildLoopWith</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a15d74c0d6159ac707f99c91219d0c6a5">llvm::SystemZELFFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a3d043cad28262fefa366ecc64c9591f1">llvm::SystemZXPLINKFrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#adca65a5406a289a41bd58993e28bb3aa">llvm::Thumb1FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a94ed22ca5dc3213bfb96e1ddbc41952e">llvm::X86FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/thumbregisterinfo/#acb75d3ebfc904675aed50ee39f619373">llvm::ThumbRegisterInfo::rewriteFrameIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvmakecompressible-cpp-/riscvmakecompressibleopt/#a76561cc6613d04a06e24640760923da2">anonymous{RISCVMakeCompressible.cpp}::RISCVMakeCompressibleOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86lowertilecopy-cpp-/x86lowertilecopy/#aa17be634e24513ab263db157b226268b">anonymous{X86LowerTileCopy.cpp}::X86LowerTileCopy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/x86machinefunctioninfo/#a8109e774fb19e0ec57444aa577358ef4">llvm::X86MachineFunctionInfo::setRestoreBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#ac0e549bf3d7f691714f73696c1df480c">llvm::SystemZELFFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#a9db07f97c8d52e506e689b789b231f0c">llvm::SystemZXPLINKFrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#af07ce77a4beea41a98862690cee5ec2d">llvm::Thumb1FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afc942a637e5d48a94d4033498b7479dd">llvm::X86FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a6824e94d9b2072a10ce5b95ae157ce50">splitLowAndHighRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo/#ae40ad0fb496b80530278bd89806de1e6">llvm::AVRRegisterInfo::splitReg</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#add05bb6a2fc43dfa726b8a1a02d1b4c0">llvm::PPCFrameLowering::updateCalleeSaves</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d22c115f5634f10ef137c93c762ebca">llvm::UpgradeDataLayoutString</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a4cc24eca5caee29bd57f43e84c285ee3">llvm::GenericCycle&lt; ContextT &gt;::verifyCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a6800237552d7755621ec154b8d93d718">llvm::GenericCycle&lt; ContextT &gt;::verifyCycleNest</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#aeac4ca2dcb29682747f7d637b47c8327">llvm::Function::viewCFG</a>.</p>

</div>
</div>

### contains() {#ab338bbeb1b837153bb97d7aad7f4dc68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool contains (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Expr, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Declaration at line 486 of file Value.cpp, definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### getOffsetFromIndex() {#a1874ee4114fb76d9b4772ea6c0daa760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; getOffsetFromIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gepoperator">GEPOperator</a> * GEP, unsigned Idx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
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



<p>Declaration at line 996 of file Value.cpp, definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### getSymTab() {#a5c3c0815d6e4c2535bc27f822f5e0960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getSymTab (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> *&amp; ST)</td>
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



<p>Declaration at line 259 of file Value.cpp, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits/#a619d61eb54e62808cef4cf2be64362d9">llvm::SymbolTableListTraits&lt; ValueSubClass, Args &gt;::addNodeToList</a>, <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits/#a9e2ac8c4fa394da00f80a521ad3ab63f">llvm::SymbolTableListTraits&lt; ValueSubClass, Args &gt;::removeNodeFromList</a> and <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits/#a1e9c2dcceebb098e6b63fd7c7aee23fd">llvm::SymbolTableListTraits&lt; ValueSubClass, Args &gt;::setSymTabObject</a>.</p>

</div>
</div>

### isUnDroppableUser() {#a912e3fffa4865ae00253b61517516e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isUnDroppableUser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * U)</td>
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



<p>Declaration at line 165 of file Value.cpp, definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

### replaceDbgUsesOutsideBlock() {#a892500981aa7cebf6ad1a8a06f9e852e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void replaceDbgUsesOutsideBlock (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Replace llvm.dbg.</p>


<ul class="doxyList ">
<li>uses of MetadataAsValue(ValueAsMetadata(V)) outside BB with New.</li>
</ul>

<p>Declaration at line 575 of file Value.cpp, definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### UseDerefAtPointSemantics {#a4025923692762bfb9a69935f9c10aeb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseDerefAtPointSemantics("use-dereferenceable-at-point-semantics", cl::Hidden, cl::init(false), cl::desc("Deref attributes and metadata infer facts at definition only"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file Value.cpp.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### HANDLE\_CONSTANT {#acf38b15c88cc9aaa1d9d16d8ef901eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_CONSTANT(Name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Value::Name##Val:                                                       \
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>("constants should be destroyed with destroyConstant");    \
    break;
</div>
</dd>
</dl>

<p>Definition at line 121 of file Value.cpp.</p>

</div>
</div>

### HANDLE\_INST {#a64ddf810a37aa06799899d388fdb6bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_INST(N, OPC, CLASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Value::InstructionVal + Instruction::OPC:                               \
    delete static_cast&lt;CLASS *&gt;(this);                                         \
    break;
</div>
</dd>
</dl>

<p>Definition at line 128 of file Value.cpp.</p>

</div>
</div>

### HANDLE\_INSTRUCTION {#a8827f21a62bce86aa16372160a0c1a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_INSTRUCTION(Name)&nbsp;&nbsp;&nbsp;/* nothing */</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file Value.cpp.</p>

</div>
</div>

### HANDLE\_MEMORY\_VALUE {#a599351901c1999079b9144b449bbd366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_MEMORY_VALUE(Name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Value::Name##Val:                                                       \
    static_cast&lt;DerivedUser *&gt;(this)-&gt;DeleteValue(                             \
        static_cast&lt;DerivedUser *&gt;(this));                                     \
    break;
</div>
</dd>
</dl>

<p>Definition at line 116 of file Value.cpp.</p>

</div>
</div>

### HANDLE\_USER\_INST {#afbebec61a87f66d24bd85056778ae42c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_USER_INST(N, OPC, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file Value.cpp.</p>

</div>
</div>

### HANDLE\_VALUE {#a1d80d7a17dae775c0b19c64d8c5e0495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_VALUE(Name)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case Value::Name##Val:                                                       \
    delete static_cast&lt;Name *&gt;(this);                                          \
    break;
</div>
</dd>
</dl>

<p>Definition at line 112 of file Value.cpp.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
