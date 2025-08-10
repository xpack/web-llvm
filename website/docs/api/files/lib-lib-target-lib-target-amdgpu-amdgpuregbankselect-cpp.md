---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AMDGPURegBankSelect.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpu-h">AMDGPU.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliselutils-h">AMDGPUGlobalISelUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnsubtarget-h">GCNSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">llvm/CodeGen/GlobalISel/CSEMIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineuniformityanalysis-h">llvm/CodeGen/MachineUniformityAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuregbankselect-cpp-">anonymous{AMDGPURegBankSelect.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect">AMDGPURegBankSelect</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/regbankselecthelper">RegBankSelectHelper</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b0ff7672275b7b589f6fe1c43569a1b">INITIALIZE_PASS_BEGIN</a> (AMDGPURegBankSelect, DEBUG_TYPE, "AMDGPU Register Bank Select", false, false) INITIALIZE_PASS_END(AMDGPURegBankSelect</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4200f6df2fb7c3d67e2b08b0fa0d0ea9">getVReg</a> (MachineOperand &amp;Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AMDGPU <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Bank</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09bc27545df3b02401428427d0b5ce6f">Select</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AMDGPU <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Bank</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc7eb5906f747358e6e0c45674cda0e">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"amdgpu-regbankselect"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Assign register banks to all register operands of G_ instructions using machine uniformity analysis. <a href="#ad78e062f62e0d6e453941fb4ca843e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getVReg() {#a4200f6df2fb7c3d67e2b08b0fa0d0ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register getVReg (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Op)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp">AMDGPURegBankSelect.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbankselect-cpp-/amdgpuregbankselect/#abceb824dea15a0f50ab19fc7126f618f">anonymous{AMDGPURegBankSelect.cpp}::AMDGPURegBankSelect::runOnMachineFunction</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a2b0ff7672275b7b589f6fe1c43569a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (AMDGPURegBankSelect, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "AMDGPU <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Bank Select", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp">AMDGPURegBankSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp">AMDGPURegBankSelect.cpp</a>.</p>

</div>
</div>

### false {#a2fc7eb5906f747358e6e0c45674cda0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU Register Bank false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp">AMDGPURegBankSelect.cpp</a>.</p>

</div>
</div>

### Select {#a09bc27545df3b02401428427d0b5ce6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AMDGPU Register Bank Select</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp">AMDGPURegBankSelect.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a70fac2d1e6e0b0c95591638ca99cae07">llvm::CombinerHelper::applyFoldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1347d52f024418efd43a77e0fcb57355">llvm::InstCombinerImpl::canonicalizeCondSignextOfHighBitExtractToSignextHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ab4702e14af79ed7cfb20ad593936460e">combineMulSelectConstOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40bb6295bf75ebb0f636376637ed518f">constantFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52fcded779c8029fdafaa9897cd3b238">llvm::createMinMaxOp</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvreader/#a8a15ec2eff468d1dc1137a8a8f20f525">llvm::logicalview::LVReader::doLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#ac66885d3ce04a263a03746461eac12b1">llvm::VPReductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a0550f165f22c1b1372bf6428191f0a9e">llvm::InstCombinerImpl::foldICmpSelectConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aa51c5fb5e986aa53dd89f9f775bc7e81">foldSelectCmpXchg</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a842f13add9ede73561cdbad22101b255">anonymous{SLPVectorizer.cpp}::HorizontalReduction::getRdxKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#ada83bd45831da890fc8e5adaf0aa3d2c">getV_CMPOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a2c6757c9a28bcbfca9f20c0d8ffd23fe">getValueOnFirstIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchiseldagtodag-cpp/#ad42177120fd9d2f2693b604658449116">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a953f3ddec823a0c7db75e73dbf550632">llvm::SIInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a122aba3e4ce982c894eee6da09b1c234">instCombineSVESel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a025e6664b2f55d2c217543c34eb1f64e">llvm::TargetLoweringBase::InstructionOpcodeToISD</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a7af4f3d780a4c92809414d5e43d98337">llvm::RecurrenceDescriptor::isAnyOfPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad5d72247c1a3137bc2c2c7aaf0000b03">isFixedVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae318fdb278df4aaf9e229584fb769b41">llvm::RecurrenceDescriptor::isMinMaxPattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a6a2d7b6d01962d7dff4c6e3e87f4575e">isSignedMinMaxClamp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a744d14408c0db57df812858803759ba1">LowerBUILD_VECTORvXi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a47c057e00771d3428bba280de009c4c8">lowerDisjointIndicesShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af682dbf33bab9c483fe52d9edd85422c">LowerMLOAD</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/logicalop-match/#a56ca0ff12cc15b489076439b061e1652">llvm::PatternMatch::LogicalOp_match&lt; LHS, RHS, Opcode, Commutable &gt;::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#afaeb891d2410d3aaf4d95fc61028f7b4">llvm::CombinerHelper::matchCastOfSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aa3f4c3db433c1eb3e4feab24f3afb7db">llvm::CombinerHelper::matchFoldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ab57fb15e1f069496b2fa0b372b9b0475">llvm::CombinerHelper::matchSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a9098323777f98b3dd53bef412554961c">llvm::CombinerHelper::matchSelectIMinMax</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6f143ae3ebc33b4f3f97e486bf7112">llvm::LegalizerHelper::narrowScalarSelect</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/bitpermutationselector/#a7084f717d525cea75708471b0acda302">anonymous{PPCISelDAGToDAG.cpp}::BitPermutationSelector::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#ac632fa4ac33de997f4fc1b02b416462c">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::Simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a002b7ea3a854166ae7ffe9d0e3e994d7">simplifySwitchOnSelectUsingRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a6594a7d514d3847ccbe52b66a49d8ee5">tryToRecognizeTableBasedCttz</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a56cb2dd18ee973c519f699213b466ade">upgradeMaskedMove</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a91100900b6eb1ae18127f1e1f8f8a40e">llvm::InstCombinerImpl::visitSwitchInst</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"amdgpu-regbankselect"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Assign register banks to all register operands of G_ instructions using machine uniformity analysis.</p>


<p>Sgpr - uniform values and some lane masks Vgpr - divergent, non S1, values Vcc - divergent S1 values(lane masks) However in some cases G_ instructions with this register bank assignment can't be inst-selected. This is solved in AMDGPURegBankLegalize.</p>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbankselect-cpp">AMDGPURegBankSelect.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
