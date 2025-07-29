---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/expandlargedivrem-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `ExpandLargeDivRem.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/expandlargedivrem-h">llvm/CodeGen/ExpandLargeDivRem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetlowering-h">llvm/CodeGen/TargetLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/integerdivision-h">llvm/Transforms/Utils/IntegerDivision.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-expandlargedivrem-cpp-">anonymous{ExpandLargeDivRem.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-expandlargedivrem-cpp-/expandlargedivremlegacypass">ExpandLargeDivRemLegacyPass</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69117a9006cbdcc4a2db996cfbf13f5">isConstantPowerOfTwo</a> (llvm::Value *V, bool SignedOp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a> (unsigned int Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a> (BinaryOperator *BO, SmallVectorImpl&lt; BinaryOperator * &gt; &amp;Replace)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a> (Function &amp;F, const TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652dfcc4921373ba8db343bebc4c5448">INITIALIZE_PASS_BEGIN</a> (ExpandLargeDivRemLegacyPass, "expand-large-div-rem", "Expand large div/rem", false, false) INITIALIZE_PASS_END(ExpandLargeDivRemLegacyPass</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc54b99db151fd3a88d53f0b2a95fc0">ExpandDivRemBits</a>("expand-div-rem-bits", cl::Hidden, cl::init(llvm::IntegerType::MAX_INT_BITS), cl::desc("div and rem instructions on integers with " "more than <N> bits are expanded."))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a> large div</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7752c64c2d688b882808f06328ad521">rem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a> large div Expand large div</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc57e539e74d607d4926436d1b7a17ec">false</a></td>
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

### INITIALIZE\_PASS\_BEGIN() {#a652dfcc4921373ba8db343bebc4c5448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (ExpandLargeDivRemLegacyPass, "expand-large-div-rem", "Expand large div/rem", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>

</div>
</div>

### isConstantPowerOfTwo() {#af69117a9006cbdcc4a2db996cfbf13f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstantPowerOfTwo (<a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * V, bool SignedOp)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a6804d9caf15411f55e7b9e9f397f0422">llvm::APInt::isNegative</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ad1b0513de876d1c85cf6268ca21b2c86">llvm::APInt::isPowerOf2</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>.</p>

</div>
</div>

### isSigned() {#a49b2092a066cfbc24bc6925bdea9682a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSigned (unsigned int Opcode)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/apint/#a44d65323d90a63e5f572fe8f44db1154">llvm::APInt::APInt</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonasmparser-cpp-/hexagonoperand/#ac2aee5b5bd6cf3275da3e9e35895fecc">anonymous{HexagonAsmParser.cpp}::HexagonOperand::CheckImmRange</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a135db5ce97b04855e9e8f44d26d30d43">llvm::detail::IEEEFloat::convertFromAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a3da3eaf2f546dd6c6f631f2e2c2436a2">llvm::detail::IEEEFloat::convertFromSignExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#a4eea8656eab72e6218242f811ec6fc1f">llvm::detail::IEEEFloat::convertFromZeroExtendedInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/ieeefloat/#af5c4dc333adfdd30afcce056b9b97484">llvm::detail::IEEEFloat::convertToInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac79ca3c2d2d74cf33684397a91846564">llvm::IRBuilderBase::CreateIntCast</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a60c8e2860ccc428282e30bf6a4d36a2c">llvm::CastInst::CreateIntegerCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae32cf891f9f15262436c301330233bad">DecodeBFLabelOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab05ba39ce6e678149dabd939c9ad4c3e">llvm::InstCombinerImpl::EvaluateInDifferentType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a0e753b1d4f854db309aac9c6ed935159">llvm::ConstantInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#a969709dd49c28865a482d8b870f87c46">llvm::ConstantInt::get</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4171c1656e5184034c3b4a5a85e2c4f7">llvm::ScalarEvolution::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8fb36df786ff6728049d25647092c350">getDivRemArgList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a5c6c520681b64fb03687d290b17f6e83">getDivRemLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a477d37efcba589f51c319373cee0294e">llvm::APSInt::getExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a87dd0d3d75417cfdea08c2fc3a2ad8e3">llvm::HexagonInstrInfo::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#af17f59ba0736ef73c0704d2361726cbe">llvm::HexagonInstrInfo::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a33c929139a72254b75f7ebb9593af9a9">llvm::InstCombinerImpl::insertRangeTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a283687c8256499fa35a1a1d387874cbe">isDivRemLibcallAvailable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6c49319d93381e455f0138e221896629">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1b7427c6c75d193f9899b8a2849ed8aa">isExtendedBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a0f78fc5fd7a7ad8a92ce3a0ba77aecf4">llvm::ARMBaseRegisterInfo::isFrameOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a16fd96ce7d6d8206ad35461a688a780f">llvm::APSInt::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#a590f094c63a53f5cda018ce31a2e541b">llvm::APSInt::isRepresentableByInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a6b456d582237b235a7f387d11e56c2bc">llvm::TargetTransformInfoImplBase::minRequiredElementSize</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsolver/#a8352b166b14a2e9bf776190e382b4733">llvm::SMTSolver::mkBVAddNoOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsolver/#a6b2ee1269a00056acaf6364551298332">llvm::SMTSolver::mkBVMulNoOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsolver/#a8993cb879dad9c5a28147852e9d681c3">llvm::SMTSolver::mkBVSubNoUnderflow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a179a8cd2adc83f28bc70fed3ee8fde0b">PerformVCVTCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a30dc6de174502314903dfcbf8d176cea">PerformVMulVCTPCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a48334652c819dffc9a133ce268693858">llvm::APInt::print</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a61a7d6f4ff5c687b725de3d5612d25dd">llvm::InstCombinerImpl::replaceInInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ae5dfa02c3403baa3d057b6264eed687d">llvm::APInt::roundToDouble</a>, <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#afede4bd63799684de5d737cd51519768">llvm::APFloatBase::semanticsIntSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apsint/#ab42308e3ef28ca0123864b24eeb98b5d">llvm::APSInt::toString</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa4cf868b89270f2f699fdee46cb572a4">llvm::InstCombinerImpl::tryFoldInstWithCtpopWithNot</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cmpinst/#a16c943accfc0b6092988d5cf6a48694b">llvm::sandboxir::CmpInst::WRAP_BOTH</a>.</p>

</div>
</div>

### runImpl() {#ae64f9cd0977a8b47570154312540d7d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool runImpl (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="#a2bc54b99db151fd3a88d53f0b2a95fc0">ExpandDivRemBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a8c5ea33ce5a61db1aedfac35723a7f5b">llvm::TargetLoweringBase::getMaxDivRemBitWidthSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>, <a href="#af69117a9006cbdcc4a2db996cfbf13f5">isConstantPowerOfTwo</a>, <a href="#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a8bb58e9357b2f891f98fbbce353155efa1ccefdf8a7414a6829f888e5071e0379">llvm::IntegerType::MAX_INT_BITS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/deadmachineinstructionelim-cpp/#a3f2d2aa9085b12e4b3136f6e64ea3030">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerinvoke-cpp/#aa0228eb7dfb2f4fd688627466fb2af17">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/aggressiveinstcombinepass/#a1d380b75a626cf6035ca021b9033e8f4">llvm::AggressiveInstCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuattributorpass/#a6b853868668b480de1fb9a5638185bbf">llvm::AMDGPUAttributorPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/annotationremarkspass/#a1dd7b1feb9652fcb6ea5e6741029b063">llvm::AnnotationRemarksPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/correlatedvaluepropagationpass/#a1672fc6d49348158aa95dbb4ae80224c">llvm::CorrelatedValuePropagationPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dataflowsanitizerpass/#a763709e61e42f6df707528b509adf8de">llvm::DataFlowSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/deadmachineinstructionelimpass/#ad3348ab2ee0fa767f8b2f39e16f78ac4">llvm::DeadMachineInstructionElimPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargedivrempass/#ab3c55956a41284798a17daed1f2d3de2">llvm::ExpandLargeDivRemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargefpconvertpass/#ac98aeadd0bb290c908220397e777c556">llvm::ExpandLargeFpConvertPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandmemcmppass/#a85fc402deca53378a8d6a952b821d9b8">llvm::ExpandMemCmpPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/finalizeiselpass/#ad2c0689c7c7707da00dbf33e6e8614c1">llvm::FinalizeISelPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrexpandpass/#af36e885f10703886f9001dd79432b77f">llvm::IndirectBrExpandPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/injecttlimappings/#a132043059b6f75e1cdca29b58c58d872">llvm::InjectTLIMappings::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instsimplifypass/#ad073cb9259c01c880086405f8776a106">llvm::InstSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/jmcinstrumenterpass/#a5d2aeb7f2893f237f1662e2f9cc19eb5">llvm::JMCInstrumenterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsshrinkwrappass/#ae988b0b1818ad722c8cfae3a649223c0">llvm::LibCallsShrinkWrapPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopdistributepass/#ab4ccb40cf0dd5fd358dd5e0f0d4d7c6f">llvm::LoopDistributePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioningpass/#ab85aee23551eb41e8d1d7e01e1fd3f98">llvm::LoopVersioningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerglobaldtorspass/#a8895fb3cf22b753143095a1552ca974a">llvm::LowerGlobalDtorsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lowerinvokepass/#a13431158a9ef331dddfb0484b37f7bee">llvm::LowerInvokePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcapelimpass/#ae4e95bbaf8d3c3a8b8df38c406a73030">llvm::ObjCARCAPElimPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarcexpandpass/#afec00b95aa5fccab1101e69496207a4a">llvm::ObjCARCExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithveclib/#ac03e0f62c8cbbdd055546686f847183c">llvm::ReplaceWithVeclib::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rewritesymbolpass/#a3a676b28a8e2daaf300ad9c5e3776c33">llvm::RewriteSymbolPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/scalarizemaskedmemintrinpass/#ab805176ab5d08e2a34fadbc760bca5a6">llvm::ScalarizeMaskedMemIntrinPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#aaec443311cb572adf0e2db9db82279ef">llvm::SLPVectorizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/unifyloopexitspass/#afa18953dc3062e2c68866c9065b12bcb">llvm::UnifyLoopExitsPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargedivrem-cpp-/expandlargedivremlegacypass/#aa7d7ea9e2d32b1837b3826c0b8ccd9ee">anonymous{ExpandLargeDivRem.cpp}::ExpandLargeDivRemLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandlargefpconvert-cpp-/expandlargefpconvertlegacypass/#acb19b315a948eddca959776d612d55bc">anonymous{ExpandLargeFpConvert.cpp}::ExpandLargeFpConvertLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-indirectbrexpandpass-cpp-/indirectbrexpandlegacypass/#a64dedd5849a9616aaa9ba3ed8010c384">anonymous{IndirectBrExpandPass.cpp}::IndirectBrExpandLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-instsimplifypass-cpp-/instsimplifylegacypass/#a3b5ea09d64637ac1796d3e3147efc69f">anonymous{InstSimplifyPass.cpp}::InstSimplifyLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowerinvoke-cpp-/lowerinvokelegacypass/#aab02bc0bf0fc5c4a4b2afe937fd6498a">anonymous{LowerInvoke.cpp}::LowerInvokeLegacyPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/replacewithvecliblegacy/#a86519aa4756de655d9faee188cf248b9">llvm::ReplaceWithVeclibLegacy::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuattributor-cpp-/amdgpuattributorlegacy/#aa9be06f303a8e9d0c728ac5fd273b383">anonymous{AMDGPUAttributor.cpp}::AMDGPUAttributorLegacy::runOnModule</a> and <a href="/web-llvm/docs/api/structs/anonymous-jmcinstrumenter-cpp-/jmcinstrumenter/#aaa4834dd00443ca395451467f8a8549e">anonymous{JMCInstrumenter.cpp}::JMCInstrumenter::runOnModule</a>.</p>

</div>
</div>

### scalarize() {#a5c0f04dd919f2fa52e52f277a68b1ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void scalarize (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * BO, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> * &gt; &amp; Replace)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aba5d97f3a14427982c1b86dafd033320">llvm::IRBuilderBase::CreateBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a303d984774b5c8af8ee4da0aa1960207">llvm::IRBuilderBase::CreateExtractElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a48ec5fcee6d2c17c723e8e67f169f948">llvm::User::dropAllReferences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a601ee49a4c4e0babf29bd1cf09036570">llvm::Instruction::eraseFromParent</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvlegalizerinfo/#a6b747313719abb32e3599ab33501ea17">llvm::SPIRVLegalizerInfo::SPIRVLegalizerInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ExpandDivRemBits {#a2bc54b99db151fd3a88d53f0b2a95fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ExpandDivRemBits("expand-div-rem-bits", cl::Hidden, cl::init(llvm::IntegerType::MAX_INT_BITS), cl::desc("div and rem instructions on integers with " "more than &lt;N&gt; bits are expanded."))</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>


<p>Referenced by <a href="#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>.</p>

</div>
</div>

### false {#acc57e539e74d607d4926436d1b7a17ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">expand large div Expand large div false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>

</div>
</div>

### rem {#ac7752c64c2d688b882808f06328ad521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">expand large div Expand large div rem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp">ExpandLargeDivRem.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#aab0971160b7ebc9ee2581f651a3b7f01">llvm::SchedBoundary::init</a> and <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a4c095bc668c91fc2d3a4df68a944793e">llvm::SchedBoundary::SchedBoundary</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
