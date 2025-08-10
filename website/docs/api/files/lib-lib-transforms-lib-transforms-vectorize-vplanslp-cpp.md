---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `VPlanSLP.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-h">VPlan.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanvalue-h">VPlanValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/vectorutils-h">llvm/Analysis/VectorUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;optional&gt;
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0e935964c3957530233849a972e1ea">getOperands</a> (ArrayRef&lt; VPValue * &gt; Values, unsigned OperandIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1907ee7981a0a84ec5ec9584555cb68">areCommutative</a> (ArrayRef&lt; VPValue * &gt; Values)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> *, 4 &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a0de1f128a2dbbc90681891fc1a68c6">getOperands</a> (ArrayRef&lt; VPValue * &gt; Values)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> (ArrayRef&lt; VPValue * &gt; Values)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the opcode of Values or ~0 if they do not all agree. <a href="#a06b4f19004df11b338ccc7e73bf47ab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4794a235e395504cd97192b10601088f">areConsecutiveOrMatch</a> (VPInstruction *A, VPInstruction *B, VPInterleavedAccessInfo &amp;IAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if A and B access sequential memory if they are loads or stores or if they have identical opcodes otherwise. <a href="#a4794a235e395504cd97192b10601088f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe85bfe8f9fdaa3a184b92862dd99d35">getLAScore</a> (VPValue *V1, VPValue *V2, unsigned MaxLevel, VPInterleavedAccessInfo &amp;IAI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implements getLAScore from Listing 7 in the paper. <a href="#abe85bfe8f9fdaa3a184b92862dd99d35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b57bf2f095fc8fe9d16442b56e58ce">LookaheadMaxDepth</a> = 5</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"vplan-slp"</td>
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

### areCommutative() {#ac1907ee7981a0a84ec5ec9584555cb68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areCommutative (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Values)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#a55743bd32282bf6f87aeb49237b1fb68">llvm::Instruction::isCommutative</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>.</p>

</div>
</div>

### areConsecutiveOrMatch() {#a4794a235e395504cd97192b10601088f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool areConsecutiveOrMatch (<a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> * A, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction">VPInstruction</a> * B, <a href="/web-llvm/docs/api/classes/llvm/vpinterleavedaccessinfo">VPInterleavedAccessInfo</a> &amp; IAI)</td>
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

<p>Returns true if A and B access sequential memory if they are loads or stores or if they have identical opcodes otherwise.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/classes/llvm/vpinterleavedaccessinfo/#a44fe021e1f4e19bb3d99a2a028330b5b">llvm::VPInterleavedAccessInfo::getInterleaveGroup</a>.</p>


<p>Referenced by <a href="#abe85bfe8f9fdaa3a184b92862dd99d35">getLAScore</a>.</p>

</div>
</div>

### getLAScore() {#abe85bfe8f9fdaa3a184b92862dd99d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getLAScore (<a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * V2, unsigned MaxLevel, <a href="/web-llvm/docs/api/classes/llvm/vpinterleavedaccessinfo">VPInterleavedAccessInfo</a> &amp; IAI)</td>
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

<p>Implements getLAScore from Listing 7 in the paper.</p>


<p>Traverses and compares operands of V1 and V2 to MaxLevel.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>


<p>References <a href="#a4794a235e395504cd97192b10601088f">areConsecutiveOrMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#abe85bfe8f9fdaa3a184b92862dd99d35">getLAScore</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#abe85bfe8f9fdaa3a184b92862dd99d35">getLAScore</a>.</p>

</div>
</div>

### getOpcode() {#a06b4f19004df11b338ccc7e73bf47ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; getOpcode (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Values)</td>
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

<p>Returns the opcode of Values or ~0 if they do not all agree.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a086f43049b2d52208b7727be22f5e604">llvm::R600InstrInfo::analyzeBranch</a>, <a href="#ac1907ee7981a0a84ec5ec9584555cb68">areCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/structs/anonymous-scalarevolution-cpp-/binaryop/#ad143f72265caa743fa9650499b48bca6">anonymous{ScalarEvolution.cpp}::BinaryOp::BinaryOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-simplifyindvar-cpp-/binaryop/#abff2b27e571ffb6e87ef6e12956a32f8">anonymous{SimplifyIndVar.cpp}::BinaryOp::BinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a33ef395caf45de82ba3568a2c8444d61">canSplitIdx</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7af5f6d50f3be3168a1d91d056c78c8c">combineToHorizontalAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#adf16e652f4ba111247577ce870fdb85f">llvm::ConstantExprKeyType::ConstantExprKeyType</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#a35a51401bc41aa572a56b74c20a89409">llvm::ConstantExprKeyType::ConstantExprKeyType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#adc81cc844c6c6c32c8be216807aa54f5">FoldBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af8c1d39848b445bea8e307b53f81c481">llvm::InstCombinerImpl::freelyInvertAllUsersOf</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/instructionuseexpr/#a63343d7bd10f61ce837992a212b7f517">anonymous{GVNSink.cpp}::InstructionUseExpr::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9affd129d19aae669647eb0d1c91f793">llvm::Instruction::getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/selectlike/#aad811cf3b50296c6f065133a96294e28">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::SelectLike::getOpCostOnBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#adad27d8740783e65067b7c2ad286aa38">llvm::sandboxir::Context::getOrCreateValueInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a1ef1466270a3df7919d1f6111447997e">llvm::Instruction::isArithmeticShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac3376e3bd632ad72252638ae43295ce4">llvm::Instruction::isBitwiseLogicOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a27997849d8982bf226891024fd68daee">llvm::Instruction::isCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5d3d315f678bc76e43b27d18e5d72829">llvm::Instruction::isEHPad</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aced8559a5380b3759af251428f024c02">llvm::Instruction::isFenceLike</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9f25788548135c3b2bee0f5d37becd77">llvm::Instruction::isFPDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a70c1f2d69b2ea2f6d7e83bb17bb9ba0a">llvm::Instruction::isFuncletPad</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aeba4ff92fbdb591fb2a1090dbda31691">llvm::Instruction::isIdempotent</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af9c2825ab53adf1bf8c9fa19ec89d986">llvm::Instruction::isIntDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#aadb443634ecdb8f3e6aa001e6d436122">llvm::Instruction::isLogicalShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a902c3b08cb9808fddc542ff284c28edb">llvm::Instruction::isNilpotent</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/instructionsstate/#a3b16378b59a09f2d469fd125bdbf19f2">anonymous{SLPVectorizer.cpp}::InstructionsState::isOpcodeOrAlt</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac5984d6827f6e6922bed00bf03ba9552">llvm::Instruction::isShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6a2d7b6d01962d7dff4c6e3e87f4575e">isSignedMinMaxClamp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcb56ab491984549c6f734b0f5b4f925">llvm::Instruction::isSpecialTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a7653277511df1034148a37520a585bb5">llvm::Instruction::isTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae6249022aded13ad98775c11881bc117">llvm::Instruction::isUnaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a51e42fbc8748c4097b19ad130cb61959">LinearizeExprTree</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gafe8eaac991f832fad7bdf7c0161150bc">LLVMGetConstOpcode</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6d418ee6f30e69c9e0bbb4c770995028">lowerV8I16Shuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvasmprinter-cpp-/spirvasmprinter/#a22518f296231106bdd60c1d4397965a6">anonymous{SPIRVAsmPrinter.cpp}::SPIRVAsmPrinter::outputExtFuncDecls</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a64949951a81f6c67ecbd51ad90374828">llvm::VPWidenEVLRecipe::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/r600isellowering-cpp/#a5dc22dc930f2a262ed4e67b2915bbb11">ReorganizeVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a6b532a3420c46c6194f80f8590cd7689">scalarize</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>.</p>

</div>
</div>

### getOperands() {#aca0e935964c3957530233849a972e1ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; VPValue *, 4 &gt; getOperands (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Values, unsigned OperandIndex)</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ac475c1bc115b2d8b03a7959be84b1ca9">getInvertibleOperands</a> and <a href="#a9a0de1f128a2dbbc90681891fc1a68c6">getOperands</a>.</p>

</div>
</div>

### getOperands() {#a9a0de1f128a2dbbc90681891fc1a68c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; SmallVector&lt; VPValue *, 4 &gt;, 4 &gt; getOperands (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vpvalue">VPValue</a> * &gt; Values)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aca0e935964c3957530233849a972e1ea">getOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### LookaheadMaxDepth {#a24b57bf2f095fc8fe9d16442b56e58ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LookaheadMaxDepth = 5</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"vplan-slp"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp">VPlanSLP.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
