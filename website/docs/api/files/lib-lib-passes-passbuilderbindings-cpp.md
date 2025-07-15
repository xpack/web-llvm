---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/passes/passbuilderbindings-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PassBuilderBindings.cpp` File Reference

<p>This file defines the C bindings to the new pass manager. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h">llvm-c/Transforms/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/aliasanalysis-h">llvm/Analysis/AliasAnalysis.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/standardinstrumentations-h">llvm/Passes/StandardInstrumentations.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h">llvm/Support/CBindingWrapping.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

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

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmpassbuilderoptions">LLVMPassBuilderOptions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper struct for holding a set of builder options for LLVMRunPasses. <a href="/web-llvm/docs/api/classes/llvm/llvmpassbuilderoptions/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d5d9c4a7ebc7a8bdbe5a55e44dc48c3">unwrap</a> (LLVMTargetMachineRef P)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72754fa176458326771f031c04a9a0d7">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a> (LLVMPassBuilderOptions, LLVMPassBuilderOptionsRef) static LLVMErrorRef runPasses(Module *Mod</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passbuilder">PassBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1501c49c84f3addfd108c2484f5674">PB</a> (Machine, PassOpts-&gt;PTO, std::nullopt, &amp;PIC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassOpts-&gt;AAPipeline)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afd1501c49c84f3addfd108c2484f5674">PB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29bd660c45b6352afc9304125087acee">registerLoopAnalyses</a> (LAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afd1501c49c84f3addfd108c2484f5674">PB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adad0fc6ef454ecb82d2be8d867615909">registerFunctionAnalyses</a> (FAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afd1501c49c84f3addfd108c2484f5674">PB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9c398dfb70860524e111965bc1a2a14">registerCGSCCAnalyses</a> (CGAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afd1501c49c84f3addfd108c2484f5674">PB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3436adb2fa793c00b5cd18b99dd73c8b">registerModuleAnalyses</a> (MAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afd1501c49c84f3addfd108c2484f5674">PB</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f45321972482ebcb5238a0bc72c3d55">crossRegisterProxies</a> (LAM, FAM, CGAM, MAM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/standardinstrumentations">StandardInstrumentations</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10fde6bea2f819ef87db20d8fe3085c7">SI</a> (Mod-&gt;getContext(), Debug, VerifyEach)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a10fde6bea2f819ef87db20d8fe3085c7">SI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8efe9e83ceb2ff61f7e6091fc8ebbe3c">registerCallbacks</a> (PIC, &amp;MAM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80362d592aa56ce616f030fbc3a0bd0">if</a> (Fun)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabda80e998791549194f388227fc4481">if</a> (VerifyEach) MPM.addPass(VerifierPass())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gae3e632706254c18142e979ad1aec63a9">LLVMRunPasses</a> (LLVMModuleRef M, const char *Passes, LLVMTargetMachineRef TM, LLVMPassBuilderOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct and run a set of passes over a module. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gae3e632706254c18142e979ad1aec63a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gaf31caae4259f8aaaac2d6cc296a3c952">LLVMRunPassesOnFunction</a> (LLVMValueRef F, const char *Passes, LLVMTargetMachineRef TM, LLVMPassBuilderOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct and run a set of passes over a function. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gaf31caae4259f8aaaac2d6cc296a3c952">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga0fe3fac04d1cb0d18d24b194794678ac">LLVMCreatePassBuilderOptions</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new set of options for a PassBuilder. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga0fe3fac04d1cb0d18d24b194794678ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga1f4b0b26dccab6bd18dc0461a4655758">LLVMPassBuilderOptionsSetVerifyEach</a> (LLVMPassBuilderOptionsRef Options, LLVMBool VerifyEach)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle adding the VerifierPass for the PassBuilder, ensuring all functions inside the module is valid. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga1f4b0b26dccab6bd18dc0461a4655758">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga0e6798311686167ea8c6d52d2c68245b">LLVMPassBuilderOptionsSetDebugLogging</a> (LLVMPassBuilderOptionsRef Options, LLVMBool DebugLogging)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Toggle debug logging when running the PassBuilder. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga0e6798311686167ea8c6d52d2c68245b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gab90315ff95335ee7bd709a1d57096083">LLVMPassBuilderOptionsSetAAPipeline</a> (LLVMPassBuilderOptionsRef Options, const char *AAPipeline)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specify a custom alias analysis pipeline for the PassBuilder to be used instead of the default one. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gab90315ff95335ee7bd709a1d57096083">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gade89b3aed22dd6f3616c0578828dfc07">LLVMPassBuilderOptionsSetLoopInterleaving</a> (LLVMPassBuilderOptionsRef Options, LLVMBool LoopInterleaving)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga5fd1b2ca28ad492f2cab4a189b56c222">LLVMPassBuilderOptionsSetLoopVectorization</a> (LLVMPassBuilderOptionsRef Options, LLVMBool LoopVectorization)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga4a8f0bbc064a868e343595d6ffdfb0b1">LLVMPassBuilderOptionsSetSLPVectorization</a> (LLVMPassBuilderOptionsRef Options, LLVMBool SLPVectorization)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga7063db6cd5a828b75a830a75011c7313">LLVMPassBuilderOptionsSetLoopUnrolling</a> (LLVMPassBuilderOptionsRef Options, LLVMBool LoopUnrolling)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gacfd7457e6582843ca42e6011418be891">LLVMPassBuilderOptionsSetForgetAllSCEVInLoopUnroll</a> (LLVMPassBuilderOptionsRef Options, LLVMBool ForgetAllSCEVInLoopUnroll)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga27d8155739262738247c2e10be936e68">LLVMPassBuilderOptionsSetLicmMssaOptCap</a> (LLVMPassBuilderOptionsRef Options, unsigned LicmMssaOptCap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga394cea3608ff09d97f3a164704ef78ce">LLVMPassBuilderOptionsSetLicmMssaNoAccForPromotionCap</a> (LLVMPassBuilderOptionsRef Options, unsigned LicmMssaNoAccForPromotionCap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga5d2827f09e9253bff90efda50f8646ba">LLVMPassBuilderOptionsSetCallGraphProfile</a> (LLVMPassBuilderOptionsRef Options, LLVMBool CallGraphProfile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga0a26bfce0c16b662c57b619fef542bde">LLVMPassBuilderOptionsSetMergeFunctions</a> (LLVMPassBuilderOptionsRef Options, LLVMBool MergeFunctions)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga48b51173f261a787eb243c86b5a012e4">LLVMPassBuilderOptionsSetInlinerThreshold</a> (LLVMPassBuilderOptionsRef Options, int Threshold)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga2845b29f9e47f8fea2befeca45b07e79">LLVMDisposePassBuilderOptions</a> (LLVMPassBuilderOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of a heap-allocated PassBuilderOptions instance. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga2845b29f9e47f8fea2befeca45b07e79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec1db240440db5948a5f72be2665b8c5">Fun</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1f52f59d0b4cc188f43fbfdccf6c54">Passes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e16e55de32fe349f3e8242166918205">Machine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> <a href="/web-llvm/docs/api/classes/llvm/llvmpassbuilderoptions">LLVMPassBuilderOptions</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a> = ...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a> = <a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a>-&gt;VerifyEach</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/passinstrumentationcallbacks">PassInstrumentationCallbacks</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d247df65c12507f447383be37d7ccb">PIC</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cfe61417446ebb812e81293bde22a29">LAM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adce09a5a0de0e3177eb00e932734af2f">FunctionAnalysisManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a571b2bbf074b46c75300bd8f14c5ab72">CGSCCAnalysisManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13293a681188ed79fb799b7f9c173b83">CGAM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85bddafa659a93a7a67c9094648259be">MAM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0544c3fe466e421738dae463968b70ba">else</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acdfbcf188e2d4a80837e89de2ccdffab">if</a>(auto Err=PB.parsePassPipeline(MPM, <a href="#a4a1f52f59d0b4cc188f43fbfdccf6c54">Passes</a>)) return <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionenginebindings-cpp/#a5fe4041db3281600b33fbb1bde23f0d2">wrap</a>(std MPM run *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">return</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67bf7f2760d0e348e8c8f4546030f0b">LLVMErrorSuccess</a></td>
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

## Description {#details}

<p>This file defines the C bindings to the new pass manager.</p>

<div class="doxySectionDef">

## Functions

### crossRegisterProxies() {#a4f45321972482ebcb5238a0bc72c3d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PB crossRegisterProxies (<a href="#a7cfe61417446ebb812e81293bde22a29">LAM</a>, <a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="#a13293a681188ed79fb799b7f9c173b83">CGAM</a>, <a href="#a85bddafa659a93a7a67c9094648259be">MAM</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a13293a681188ed79fb799b7f9c173b83">CGAM</a>, <a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="#a7cfe61417446ebb812e81293bde22a29">LAM</a>, <a href="#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

### DEFINE\_SIMPLE\_CONVERSION\_FUNCTIONS() {#a72754fa176458326771f031c04a9a0d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEFINE_SIMPLE_CONVERSION_FUNCTIONS (<a href="/web-llvm/docs/api/classes/llvm/llvmpassbuilderoptions">LLVMPassBuilderOptions</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>

</div>
</div>

### if() {#acdfbcf188e2d4a80837e89de2ccdffab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (<a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a>-&gt; AAPipeline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a>, <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a582d0050c740c1f23bce6bc0c8c5b189">llvm::AbstractCallSite::AbstractCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumachinefunction/#a068641b222182c6ca0412660993bf1fe">llvm::AMDGPUMachineFunction::AMDGPUMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/isainfo/amdgputargetid/#a620c903fbe109239c38c7fc8ac7b6298">llvm::AMDGPU::IsaInfo::AMDGPUTargetID::AMDGPUTargetID</a>, <a href="/web-llvm/docs/api/structs/llvm/diagnosticinfooptimizationbase/argument/#a1aa19965a8f70cf0a0848106b1bc885c">llvm::DiagnosticInfoOptimizationBase::Argument::Argument</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ab3de6826079ac5f3ca5f7ef28dd3d9fb">anonymous{AsmWriter.cpp}::AssemblyWriter::AssemblyWriter</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout/#af3fa75b45aafa6c528042df53446d8e1">llvm::jitlink::BasicLayout::BasicLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphdotinfo/#adc6bb41940850bb2ae61ef5895310618">llvm::CallGraphDOTInfo::CallGraphDOTInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonnewvaluejump-cpp/#a8d3e918d874e8e80cf9a403e8ea59e32">canBeFeederToNewValueJump</a>, <a href="/web-llvm/docs/api/classes/llvm/genericscheduler/#a0aa33f27fbf7be1e7e53512ceb6de885">llvm::GenericScheduler::checkAcyclicLatency</a>, <a href="/web-llvm/docs/api/classes/llvm/codegenpassbuilder/#a94d7ce2e38cb6acae735d6edb74c8fa7">llvm::CodeGenPassBuilder&lt; AMDGPUCodeGenPassBuilder, GCNTargetMachine &gt;::CodeGenPassBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#af096fb0448f7ae66e40a5572388d3eb3">llvm::dwarf_linker::classic::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/debuginfodserver/#a146c3973caa3e8f160a781b1fa91b248">llvm::DebuginfodServer::DebuginfodServer</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#aa1d21b1024d9925b46d10fcd11e0483c">anonymous{DeadStoreElimination.cpp}::DSEState::DSEState</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#aef3ee50c530039dd44c410b678a54ec6">llvm::DwarfDebug::DwarfDebug</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/dwarfobjinmemory/#aa19f707b77c01709bba51c751b77f288">anonymous{DWARFContext.cpp}::DWARFObjInMemory::DWARFObjInMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#aa555a8e9d0e824277bb9ed7f0b813639">llvm::DWARFVerifier::DWARFVerifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a61e2de2c4987a7fdaf09251933714262">eliminateConstraints</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#abb12e569451bee60098c4608b8ca8fa5">llvm::SystemZPostRASchedStrategy::enterMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a88c9308b16c3935bc567d76748a30e05">llvm::Expected&lt; std::unique_ptr&lt; InFlightAlloc &gt; &gt;::Expected</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a4f8d24ff610fcb7ad32c767d167be350">llvm::Expected&lt; std::unique_ptr&lt; InFlightAlloc &gt; &gt;::Expected</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liverangeshrink-cpp/#a75ee109226025aaaf7373a0dca56341a">FindDominatedInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#a409abf8b151a61b0adacda9229f3cc21">findReturnsToZap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvevptblockpass-cpp/#ab65fd688ebdc8951019a8d796ebcdae5">findVCMPToFoldIntoVPST</a>, <a href="/web-llvm/docs/api/structs/anonymous-sifoldoperands-cpp-/foldcandidate/#a22926b4547ee17e802fe12e69ca53915">anonymous{SIFoldOperands.cpp}::FoldCandidate::FoldCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/funcpgoinstrumentation/#a4745567b4c976c8dd075125fff13eb54">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::FuncPGOInstrumentation</a>, <a href="/web-llvm/docs/api/classes/llvm/functionsummary/#a241573674bcf98689b6c224b05d90f70">llvm::FunctionSummary::FunctionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnusersgprusageinfo/#aefc8f0b6a7216b0b236399cd3235471c">llvm::GCNUserSGPRUsageInfo::GCNUserSGPRUsageInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodes/#ae0488ec3d2973d61223a316e88988b65">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodes::getAnalysisUsage</a>, <a href="/web-llvm/docs/api/classes/llvm/clause/#adb3d803ae6c5db871313c6154409c8cd">llvm::Clause::getFormattedParserClassName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinemoduleinfo-cpp/#a84b611106739b9bc347338219f73be29">getLocCookie</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifoldoperands-cpp/#a7fcb99675ac619b90ab5d7c2eec0a482">getRegOpRC</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonexpandcondsets-cpp-/hexagonexpandcondsets/#a320f430bcb4b19adc1c60ddb4de3a923">anonymous{HexagonExpandCondsets.cpp}::HexagonExpandCondsets::HexagonExpandCondsets</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagoninstrinfo-cpp-/hexagonpipelinerloopinfo/#a6907f6a41468c8a1f73099a44238ab21">anonymous{HexagonInstrInfo.cpp}::HexagonPipelinerLoopInfo::HexagonPipelinerLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a14d72f43eb0c681f84fc9a00c9621941">if</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnschedstage/#a02add63fe5ce109718dea7e87b1db3c1">llvm::GCNSchedStage::initGCNRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64deadregisterdefinitionspass-cpp/#a0fb33ddf5cf6eccb986131394311419e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64redundantcopyelimination-cpp/#af884214031cdb18344d85b5d4c422fef">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64speculationhardening-cpp/#aaf42ae80200bb2380ef4be8ff9c28402">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a0c644c1ec65bfe3ab19a7ac9d5e0aeab">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchmergebaseoffset-cpp/#a735102341f94b533b3c6b75f22989db4">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinsertvsetvli-cpp/#aeab9aaa0283d5249c25d93393677af94">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmergebaseoffset-cpp/#a1479c4cd799c1d374d1c82afeeb60b1e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvpushpopoptimizer-cpp/#acecdec4e0d9b07b4adf50057d15b5a38">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smepeepholeopt-cpp/#aed0d70e55a261450cb76cb7f615977dc">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callframeoptimization-cpp/#a91d092e016c6260bf8a84260975ae781">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ad73240db48b2eda2b2ca2ce38530c552">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentMaskedLoadOrStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a6760a5137f8e0ec21dbd7b99e61b52ed">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxpeephole-cpp/#acc457a91c46e1aa851b09581bc3c086a">isCVTAToLocalCombinationCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registercoalescer-cpp/#aaeffdea43602557f6c520f6b9501a491">isMoveInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/linecoveragestats/#a2d4766455bf8cead5045a6901e156704">llvm::coverage::LineCoverageStats::LineCoverageStats</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#a5a4040326a09f994f2b5481cf5c8da82">llvm::LoadAndStorePromoter::LoadAndStorePromoter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a84f17de21891f3bfb04410592e553b63">lowerV4I32Shuffle</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#aff890ddd726ba815dfa456b4a5b6f432">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::LowOverheadLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance/#a9bcf42be7435217d79cd175d4e6993d7">anonymous{LoopStrengthReduce.cpp}::LSRInstance::LSRInstance</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#ae26462941069e163c658782b4132b79d">llvm::mca::LSUnitBase::LSUnitBase</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoabstractfixupentry/#a7a5c724a4788135ad66edb2be0a81927">llvm::object::MachOAbstractFixupEntry::MachOAbstractFixupEntry</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingnormalizationheap/#a47bf37cfb84a6a9ee54d45950038aa11">llvm::yaml::MappingNormalizationHeap&lt; TNorm, TFinal &gt;::MappingNormalizationHeap</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#a75538db633297fb9c0b91ea5a16c5b72">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::ModuleBitcodeWriterBase</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/nodemetadata/#a4e49e132a088b8a63b33ebc18e6d5108">llvm::PBQP::RegAlloc::NodeMetadata::NodeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a78a93424a800f37fc3a2162c836c9eee">llvm::NVPTXTargetMachine::NVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/parameterpack/#a0c5926c3d0b74a5d0a9372345f35d572">ParameterPack::ParameterPack</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a322fc14d985cd25592d641ab24cc787e">llvm::PassBuilder::PassBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationuse/#a016467155ff27477979a58b78577db80">llvm::PGOInstrumentationUse::PGOInstrumentationUse</a>, <a href="/web-llvm/docs/api/structs/reachabilityqueryinfo/#ac7e0dd79c719ac786282002e7b96f8a4">ReachabilityQueryInfo&lt; ToTy &gt;::ReachabilityQueryInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#a32ce353011ca5bcaf6112536aec4c098">reportTranslationError</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresultswrapperpass/#a47ee17feac90f644d8afe91156ae9ddf">llvm::AAResultsWrapperPass::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64postcoalescerpass-cpp-/aarch64postcoalescer/#af7c68f72faddb47f4a574fbd77f55806">anonymous{AArch64PostCoalescerPass.cpp}::AArch64PostCoalescer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#a8305613a915321631b70e8f26e2d55d6">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-tailduplication-cpp-/tailduplicatebaselegacy/#a78a8906bfe5ee3db7d500fa09d238b8b">anonymous{TailDuplication.cpp}::TailDuplicateBaseLegacy::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinepipeliner/#a292abfa5a62a1fd7b53592085a48e651">llvm::MachinePipeliner::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/removeloadsintofakeuses/#a207cce78de7e84e6885684960f5c4f50">RemoveLoadsIntoFakeUses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerldslegacy/#acfe402ed12ef3aa3f9b6b75a60baeb33">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDSLegacy::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a4bda9a7c3b3d5d112826474bc35081e0">llvm::SanitizerCoveragePass::SanitizerCoveragePass</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzpostraschedstrategy/#a9ee4cac33c533fe9bc0b5b0147475c38">llvm::SystemZPostRASchedStrategy::schedNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/machineschedulerbase/#a5d9f088a58ed26977308b92dba6c50f6">anonymous{MachineScheduler.cpp}::MachineSchedulerBase::scheduleRegions</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowertypetests-cpp-/scopedsavealiaseesandused/#aa02d191d0f55ac0d1a4921d778d0fe63">anonymous{LowerTypeTests.cpp}::ScopedSaveAliaseesAndUsed::ScopedSaveAliaseesAndUsed</a>, <a href="/web-llvm/docs/api/classes/anonymous-veiseldagtodag-cpp-/vedagtodagisel/#a6dfb172984c1398289e06ed19df24a19">anonymous{VEISelDAGToDAG.cpp}::VEDAGToDAGISel::selectADDRrri</a>, <a href="/web-llvm/docs/api/classes/llvm/genericschedulerbase/#a8668556014566994c07b21391762551b">llvm::GenericSchedulerBase::setPolicy</a>, <a href="/web-llvm/docs/api/structs/llvm/sgprspillbuilder/#a4a1143f3929f3258aebb54b4bef12082">llvm::SGPRSpillBuilder::SGPRSpillBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/simachinefunctioninfo/#a80f6630b845109786f0840f4b15737f9">llvm::yaml::SIMachineFunctionInfo::SIMachineFunctionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#ab2354d93dbb7ffbde58e687309f44fad">simplifyAMDGCNImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkandhoistlicmflags/#a30d4121b007bf8064374e069fd2de689">llvm::SinkAndHoistLICMFlags::SinkAndHoistLICMFlags</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a5366dad88d5f63bc1c27ffc54d351201">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::SlotData</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a27558ac85c5bc3b45f39b3a46d2d858e">anonymous{ThinLTOBitcodeWriter.cpp}::splitAndWriteThinLTOBitcode</a>, <a href="/web-llvm/docs/api/structs/llvm/cgdata/streamcachedata/#aee20fb462bed3b8b7e160a5e66a6d4f3">llvm::cgdata::StreamCacheData::StreamCacheData</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9bc1c70c28eb2f5a53ad0dcac4c56b4d">llvm::StringRef::StringRef</a>, <a href="/web-llvm/docs/api/classes/threadsafetrierawhashmapbase/impltype/#a831302f460304e1a0f0256fd8b18dea1">llvm::ThreadSafeTrieRawHashMapBase::ImplType::TrailingObjects</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aba1e9ea5dd5dfc2b1559cb6cef8b4854">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::tryToPreserveWithoutAddingAssume</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a2babcc960233b1e1c8c61a91283b955a">llvm::WebAssemblyDebugValueManager::WebAssemblyDebugValueManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a>, <a href="/web-llvm/docs/api/classes/workloadimportsmanager/#a153fc7b2387346443f6c6503cc92b47d">WorkloadImportsManager::WorkloadImportsManager</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a51cfff6dff330a39d19c88e0ccd8abf1">anonymous{X86AsmBackend.cpp}::X86AsmBackend::X86AsmBackend</a>.</p>

</div>
</div>

### if() {#ac80362d592aa56ce616f030fbc3a0bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (<a href="#aec1db240440db5948a5f72be2665b8c5">Fun</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a3b988beeca0390fa8fa653d17bded384">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::addPass</a>, <a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>, <a href="#aec1db240440db5948a5f72be2665b8c5">Fun</a>, <a href="#a4a1f52f59d0b4cc188f43fbfdccf6c54">Passes</a>, <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### if() {#aabda80e998791549194f388227fc4481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (<a href="#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a4a1f52f59d0b4cc188f43fbfdccf6c54">Passes</a>, <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a> and <a href="#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a>.</p>

</div>
</div>

### PB() {#afd1501c49c84f3addfd108c2484f5674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassBuilder PB (<a href="#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a>-&gt; PTO, std::nullopt, &amp; PIC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a> and <a href="#ad4d247df65c12507f447383be37d7ccb">PIC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateassume/#aa7635fd4cc1a1414a4be9a72b8f29d2d">llvm::PredicateAssume::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatebase/#ad2570b07cd4c91f7324999c3b49f0ef6">llvm::PredicateBase::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatebranch/#a7a5d35dd8f5f44ff6e1f768687a60473">llvm::PredicateBranch::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateswitch/#a80fbe46a5c413a13cfe3d906626a587c">llvm::PredicateSwitch::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatewithedge/#af8b1b25f3060319ac1a51210a72f2765">llvm::PredicateWithEdge::classof</a>, <a href="#a4f45321972482ebcb5238a0bc72c3d55">crossRegisterProxies</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcasmprinter/#a8dce3e9284d907db3457ebbfc74909f7">anonymous{PPCAsmPrinter.cpp}::PPCAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateinfoannotatedwriter/#a84fe7c49603300369fa9dbf87ac1449d">llvm::PredicateInfoAnnotatedWriter::emitInstructionAnnot</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinelooputils-cpp-/#aff0a1cdc0a759d052259cb36a260ce10">anonymous{MachineLoopUtils.cpp}::findEquivalentInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a71bb0396fb78bb7298d96df79bbf2200">llvm::HexagonInstrInfo::findLoopInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloopinfo/#a80b0e6e28849491c5b267be8ffc909b4">llvm::MachineLoopInfo::findLoopPreheader</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-predicateinfo-cpp-/#a9db24ad92c2d78d94c6535a8d7f57d7f">anonymous{PredicateInfo.cpp}::getBlockEdge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-predicateinfo-cpp-/#a83f425b186a8621e55c765eadc4b994b">anonymous{PredicateInfo.cpp}::getBranchBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-predicateinfo-cpp-/#ad79716916ecc768bcdcdf4c478721a8b">anonymous{PredicateInfo.cpp}::getBranchTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a67c3f4d1c4060fa218ee31e2088baa6b">llvm::AArch64TargetMachine::getSubtargetImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcmcinstlower-cpp/#a8aa470cbd092a0baa198faf2e5174f94">GetSymbolRef</a>, <a href="#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="#aabda80e998791549194f388227fc4481">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp/#a3b1b9803f5e070a03a99018fc737babb">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/blockfreqquery/#af8c521993231c6aa85baba8f8c23b828">llvm::orc::BlockFreqQuery::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a2b97735452295d7091f55cfaf309ad4c">anonymous{PassBuilder.cpp}::parseRegAllocFastPassOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#aa6dcb5a067510ae66e6c6ff91840dd75">anonymous{SIModeRegister.cpp}::SIModeRegister::processBlockPhase2</a>, <a href="#aa9c398dfb70860524e111965bc1a2a14">registerCGSCCAnalyses</a>, <a href="#adad0fc6ef454ecb82d2be8d867615909">registerFunctionAnalyses</a>, <a href="#a29bd660c45b6352afc9304125087acee">registerLoopAnalyses</a>, <a href="#a3436adb2fa793c00b5cd18b99dd73c8b">registerModuleAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a50e2c161ce287abb803123ade461704a">llvm::AArch64TargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ab727dbb342900913787fc58840a3c002">llvm::AMDGPUTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine/#a4d46609394256ee755db3484c4eb6639">llvm::BPFTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/directxtargetmachine/#afe8c3dac47046a33c795f3de88524692">llvm::DirectXTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#aaa0bbd44904a73edd530500b753621c0">llvm::HexagonTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a301180369f0e5f22cceb79f2f7c9220e">llvm::NVPTXTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/passplugin/#a4527a2b697878c3dc1017ab1793664b1">llvm::PassPlugin::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a2a82fa8c8dee39214b649d29529e053d">llvm::RISCVTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a44688b03d5c4416b3dcb4ac32b49875d">llvm::SPIRVTargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#a1e1f9faf84cda8d3de61c3db4fbe5692">llvm::X86TargetMachine::registerPassBuilderCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#ac9f32ac9aec23e32f0a216c1277ab34d">RegisterPassPlugins</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofflatteningpass/#a13390fcce3ec8b52ef55488e967081c5">llvm::PGOCtxProfFlatteningPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonlooprescheduling/#a3289c50be003939c64bcb6f7f4d92887">anonymous{HexagonBitSimplify.cpp}::HexagonLoopRescheduling::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a> and <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#a5ec029c4325b9b001f8fa6e887825ea1">llvm::HexagonTargetMachine::~HexagonTargetMachine</a>.</p>

</div>
</div>

### registerCallbacks() {#a8efe9e83ceb2ff61f7e6091fc8ebbe3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SI registerCallbacks (<a href="#ad4d247df65c12507f447383be37d7ccb">PIC</a>, &amp; MAM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="#ad4d247df65c12507f447383be37d7ccb">PIC</a>.</p>

</div>
</div>

### registerCGSCCAnalyses() {#aa9c398dfb70860524e111965bc1a2a14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PB registerCGSCCAnalyses (<a href="#a13293a681188ed79fb799b7f9c173b83">CGAM</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a13293a681188ed79fb799b7f9c173b83">CGAM</a> and <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

### registerFunctionAnalyses() {#adad0fc6ef454ecb82d2be8d867615909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PB registerFunctionAnalyses (<a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a83c7e5ca51099e4efa895791a02fb0ed">FAM</a> and <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

### registerLoopAnalyses() {#a29bd660c45b6352afc9304125087acee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PB registerLoopAnalyses (<a href="#a7cfe61417446ebb812e81293bde22a29">LAM</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a7cfe61417446ebb812e81293bde22a29">LAM</a> and <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

### registerModuleAnalyses() {#a3436adb2fa793c00b5cd18b99dd73c8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PB registerModuleAnalyses (<a href="#a85bddafa659a93a7a67c9094648259be">MAM</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="#a85bddafa659a93a7a67c9094648259be">MAM</a> and <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

### SI() {#a10fde6bea2f819ef87db20d8fe3085c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StandardInstrumentations SI (<a href="#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>-&gt; getContext=(), <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a>, <a href="#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a>, <a href="#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a> and <a href="#acf9a76b441b49648ba97e4a40c3ad5f6">VerifyEach</a>.</p>

</div>
</div>

### unwrap() {#a3d5d9c4a7ebc7a8bdbe5a55e44dc48c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine * unwrap (<a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a> P)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CGAM {#a13293a681188ed79fb799b7f9c173b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CGSCCAnalysisManager CGAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#a4f45321972482ebcb5238a0bc72c3d55">crossRegisterProxies</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a3c2e12459e81e47a53dc49484af24bc2">llvm::PassBuilder::crossRegisterProxies</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#ad2d3999ee96b77c4c40f4d747609f205">llvm::PassBuilder::registerCGSCCAnalyses</a>, <a href="#aa9c398dfb70860524e111965bc1a2a14">registerCGSCCAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a>.</p>

</div>
</div>

### else {#a0544c3fe466e421738dae463968b70ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">else</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
    <a href="/web-llvm/docs/api/namespaces/llvm/#a79ab9199d2ba6a1c9cac2b79efc194a3">ModulePassManager</a> MPM
</div>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9bc1c70c28eb2f5a53ad0dcac4c56b4d">llvm::StringRef::StringRef</a>.</p>

</div>
</div>

### FAM {#a83c7e5ca51099e4efa895791a02fb0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionAnalysisManager FAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ae270226dc1d6b924308716c8b482b76d">llvm::AMDGPULibCalls::AMDGPULibCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pgoctxprofflattening-cpp-/#a1d1a012c6e6975567125e16a0e788cbd">anonymous{PGOCtxProfFlattening.cpp}::areAllBBsReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a946282957319b8c23ab9f169abb504c4">computeHeuristicUnrollFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a52e95fe46f358afc3b0006f256f9d487">computeVirtualCallSiteTypeInfoMap</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineorder-cpp-/costbenefitpriority/#a3dd918c45f346fbd6ccd9cad368e92e0">anonymous{InlineOrder.cpp}::CostBenefitPriority::CostBenefitPriority</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineorder-cpp-/costpriority/#a73d44fb96c96381e8d19d4558fba463b">anonymous{InlineOrder.cpp}::CostPriority::CostPriority</a>, <a href="#a4f45321972482ebcb5238a0bc72c3d55">crossRegisterProxies</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a3c2e12459e81e47a53dc49484af24bc2">llvm::PassBuilder::crossRegisterProxies</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a7e1da8085095c6d808713b280edb143b">anonymous{SampleProfile.cpp}::SampleProfileLoader::doInitialization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a740b270dfd80a81a0765fb1d31930828">eliminateDeadCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesupdater/#a53810b3b6ca8d3846b024899661c5e4a">llvm::FunctionPropertiesUpdater::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesupdater/#a8ce3135b0a1f6d6c05a38f92126bc526">llvm::FunctionPropertiesUpdater::finishAndTest</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo/#a886864b4db05ccf27a372a475521511a">llvm::FunctionPropertiesInfo::FunctionPropertiesUpdater</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#aaa89f605828072564b1ef10f730a67a3">getDefaultInlineAdvice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a69cac14aa225532f4e20b4bbeae62c">llvm::getDefaultInlineOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesinfo/#a33b6380c72c488ab1713ff6b70cf2a66">llvm::FunctionPropertiesInfo::getFunctionPropertiesInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inlineorder-cpp-/#abe75a2a872550eb0c6cc23a2b98fa8a4">anonymous{InlineOrder.cpp}::getInlineCostWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7acaa9d2987b3c0842cc1a758bfcb0d0">llvm::getInlineOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a903adbd42316e51df3cda640d664aa65">llvm::getReplayInlineAdvisor</a>, <a href="#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#aa64f6bcd5ace031369edc14aa406d745">incorporateNewSCCRange</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ace3e6b1b364abb13d8c1b1a79a971481">llvm::AMDGPULibCalls::initFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a12c711c62171c14dcedca2db5874d33e">llvm::SelectionDAGISel::initializeAnalysisResults</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#aa6f227fc16925fab1dac5812dc6d0cd6">llvm::InlinerPass::InlinerPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcount-cpp-/instcount/#a2f6d5d0af5c247dfbf0a42a84559ec23">anonymous{InstCount.cpp}::InstCount::InstVisitor&lt; InstCount &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a899698594c66589eab9bdca89c843798">isArgUnmodifiedByAllCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec0271fd9fb951b494325444c5e71225">llvm::lintFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a0106bab2d4d5ef7149415e2af1dfb180">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::lowerFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a41245c88cdf19ddbfe8a2dffba0a500d">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::LowerTypeTestsModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineorder-cpp-/mlpriority/#aaa9c6726a952a6c1217e5ea6333649ee">anonymous{InlineOrder.cpp}::MLPriority::MLPriority</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#adfb981cb8865a526a79cabb5e74d1034">llvm::ModuleInlinerPass::ModuleInlinerPass</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/blockfreqquery/#af8c521993231c6aa85baba8f8c23b828">llvm::orc::BlockFreqQuery::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a42ff11c63c1a675d13cc97eaec48d621">promoteIndirectCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedcfgcheckerinstrumentation/#aed649cf558f93dc41694657bc7f2442c">llvm::PreservedCFGCheckerInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#af9903a32cb913723bc7608f6544995d1">llvm::PassBuilder::registerFunctionAnalyses</a>, <a href="#adad0fc6ef454ecb82d2be8d867615909">registerFunctionAnalyses</a>, <a href="/web-llvm/docs/api/classes/anonymous-selectoptimize-cpp-/selectoptimizeimpl/#ae454ad67b6e4fa9846a5395dc76759d6">anonymous{SelectOptimize.cpp}::SelectOptimizeImpl::run</a>, <a href="/web-llvm/docs/api/structs/llvm/adcepass/#a164c2d5f016f5cde2edc6c402dca72cb">llvm::ADCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/addresssanitizerpass/#a987afb1c68c5891e0b9a67cdac48147d">llvm::AddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/alwaysinlinerpass/#ac95b8d75e282ac5dbb2ed47ae1e1c88b">llvm::AlwaysInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuannotateuniformvaluespass/#ad40e073c46402aba328eb57891116b74">llvm::AMDGPUAnnotateUniformValuesPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuattributorpass/#a6b853868668b480de1fb9a5638185bbf">llvm::AMDGPUAttributorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpreparepass/#a09ffc2a128b37269498bbcabc7f145d4">llvm::AMDGPUCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuiseldagtodagpass/#a50f97f48ab6353d9bb2bc36ce592c7e4">llvm::AMDGPUISelDAGToDAGPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulatecodegenpreparepass/#a5a4ff24504b852091b900d036f556885">llvm::AMDGPULateCodeGenPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/amdgpuswlowerldspass/#a60fde742e4c1eaef19a09e78c111cd6a">llvm::AMDGPUSwLowerLDSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentpromotionpass/#afe0f49f9daec2532b14ded30ed46ff28">llvm::ArgumentPromotionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assumptionanalysis/#aeb8f2cc893c02d3d5a926b69bab89185">llvm::AssumptionAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorcgsccpass/#a305cbdd90350f05f5ee772811d596ded">llvm::AttributorCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightcgsccpass/#a1725467ef5883a44e7777d681c6a4d32">llvm::AttributorLightCGSCCPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorlightpass/#af4dc3e41c843da6385d1252386d4c03e">llvm::AttributorLightPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/attributorpass/#aba65d47dce0a15a90eb4e519ffc4929c">llvm::AttributorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrpreparepass/#a9281dc805301bc24be1f5401e30a878f">llvm::CallBrPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphdotprinterpass/#a7d72837594bc13f77f2d84bcfd0752de">llvm::CallGraphDOTPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphviewerpass/#aaea10b30adce800d7d54b5394a49567b">llvm::CallGraphViewerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cfguardpass/#a0d01e5f89b3ff7eb3f081f3ec59d27bb">llvm::CFGuardPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgprofilepass/#ab84e768b0ca66104a03d4dd6f96422fe">llvm::CGProfilePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/controlheightreductionpass/#aa07878663a309c8f4a4537b971c6d3b0">llvm::ControlHeightReductionPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/coroannotationelidepass/#a411202dc502ac666302ba81c40e94b10">llvm::CoroAnnotationElidePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dataflowsanitizerpass/#a763709e61e42f6df707528b509adf8de">llvm::DataFlowSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/debugassignmenttrackinganalysis/#a5bb8380db596f4d29d331b41ff23eddf">llvm::DebugAssignmentTrackingAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/debugassignmenttrackingprinterpass/#a2fca7dac7d7904748ce1fd08da363d2a">llvm::DebugAssignmentTrackingPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceanalysis/#ae9ba585a33cb816f623b9b8ddf472d3a">llvm::DependenceAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dependenceanalysisprinterpass/#a94874ca66100ea29adacb124f5d73db0">llvm::DependenceAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/divrempairspass/#a4247592199f0303b2d61eb171b2acdd1">llvm::DivRemPairsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraitsprinter/#a08f94d0dd9cf5bd433019e64b44d0d58">llvm::DOTGraphTraitsPrinter&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraitsviewer/#a785d4e2677b22a4dc41713c1e82c492f">llvm::DOTGraphTraitsViewer&lt; AnalysisT, IsSimple, GraphT, AnalysisGraphTraitsT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfehpreparepass/#aa5ae7b5c2898ddfa38ede1415c5d6d3c">llvm::DwarfEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilresourceaccess/#a1d78f24c9cef5813c0cb9aea5b00b183">llvm::DXILResourceAccess::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargedivrempass/#ab3c55956a41284798a17daed1f2d3de2">llvm::ExpandLargeDivRemPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandlargefpconvertpass/#ac98aeadd0bb290c908220397e777c556">llvm::ExpandLargeFpConvertPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/expandmemcmppass/#a85fc402deca53378a8d6a952b821d9b8">llvm::ExpandMemCmpPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpropertiesanalysis/#a99dfe51a88eeff9511a30dbf83429642">llvm::FunctionPropertiesAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontomachinefunctionpassadaptor/#a1c8aea757190a42fd931c0d95a4f2721">llvm::FunctionToMachineFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcfunctionanalysis/#ac5aa6845030bc914c7c26ab65e25984e">llvm::GCFunctionAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcloweringpass/#aa642143ff84b39a1e644a6435f69b643">llvm::GCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovprofilerpass/#abe3a54029a1d4094373deb485452f033">llvm::GCOVProfilerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaloptpass/#a0be1afba37502be6858f2a1c38955be8">llvm::GlobalOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globalsaa/#a13e2d1113ed664d73521d89676ba6e9d">llvm::GlobalsAA::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hotcoldsplittingpass/#a1428bc0c1945db2bcb0bc0b17447c18c">llvm::HotColdSplittingPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hwaddresssanitizerpass/#a0ab6bbfe1dc498f2c9a8603d672fbb1b">llvm::HWAddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrexpandpass/#af36e885f10703886f9001dd79432b77f">llvm::IndirectBrExpandPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inferfunctionattrspass/#a43509c520610b43c4b366bee12dc1f4b">llvm::InferFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/inlinecostannotationprinterpass/#aa0abf6fac51bc051d817b1f71c921098">llvm::InlineCostAnnotationPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinesizeestimatoranalysis/#a94e72f48c5e88c1225c7daf679ce7d69">llvm::InlineSizeEstimatorAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofilingloweringpass/#a610148cfab0328ada1642b17b9a9e71c">llvm::InstrProfilingLoweringPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/instructionnamerpass/#ab1441d48ca950f93ea762289bcaa19f4">llvm::InstructionNamerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedaccesspass/#ae66f66ef855bdcccfe7802d81f9a816a">llvm::InterleavedAccessPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/interleavedloadcombinepass/#abd04f9ee840b4323bdb0bffe6a02a5f6">llvm::InterleavedLoadCombinePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ipsccppass/#a7c77a408787021dc65c12646cee2ac43">llvm::IPSCCPPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/iroutlinerpass/#a5b9a8fe2c3b6834817b2c12b08441cff">llvm::IROutlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraphanalysis/#a2b4c0dcc83d56146b52f6825c093b9db">llvm::LazyCallGraphAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueanalysis/#a47fb597446dc912e21892c858307fe73">llvm::LazyValueAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsshrinkwrappass/#ae988b0b1818ad722c8cfae3a649223c0">llvm::LibCallsShrinkWrapPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessanalysis/#ac40e17cfabf3d1b9b5806415a1e7ac0b">llvm::LoopAccessAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopextractorpass/#ac1cd83190da80057c6903402d80cc1f7">llvm::LoopExtractorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsinkpass/#a11eda417d0372700a9b48e41f267ab92">llvm::LoopSinkPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionanalysis/#ad42039ed34bfec0a741fa6986ecc8bea">llvm::MachineFunctionAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/memorysanitizerpass/#adfd94cfcef9d896734905bd5a18a05df">llvm::MemorySanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofcontextdisambiguation/#ac43814024a542d89728f88411b553e6d">llvm::MemProfContextDisambiguation::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memprofusepass/#a301e9c18f7576c32229ca4c2a06fb8e4">llvm::MemProfUsePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/metarenamerpass/#a1f547e81e18e412faa9f0a8a71cbd90c">llvm::MetaRenamerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindexanalysis/#a2aa0bcdd9165815fc18c689df7f2c7f5">llvm::ModuleSummaryIndexAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduletopostordercgsccpassadaptor/#a0ff99def687659818bdb4a25afd82c94">llvm::ModuleToPostOrderCGSCCPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/mustbeexecutedcontextprinterpass/#a1b1a19034ac7bbb0481e54e850fc431a">llvm::MustBeExecutedContextPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/numericalstabilitysanitizerpass/#aa05e97761e23096ba7621f0ad28c05ed">llvm::NumericalStabilitySanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptcgsccpass/#a9d4366d9c2f6de53d6f2edce548577ab">llvm::OpenMPOptCGSCCPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpoptpass/#ad0812a5ba88f8645505134a108f639b2">llvm::OpenMPOptPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/partialinlinerpass/#a022b0aa595cef197b5b0c655cd18ad9c">llvm::PartialInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#a6d74effaad77f6ecb91e1806993cda8f">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoforcefunctionattrspass/#a5a7425ff46058c5adf7da1d9a58c4000">llvm::PGOForceFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgen/#a9cff4300652b1ae7f59c26011099ac65">llvm::PGOInstrumentationGen::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationuse/#a11847c7e88a21b5076fb1cb5e2f7f5e1">llvm::PGOInstrumentationUse::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgomemopsizeopt/#a01227f37509d10916de26411ab363d6b">llvm::PGOMemOPSizeOpt::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/preiselintrinsicloweringpass/#a6c4bdf5cd38f45ec8052f395f32f63ee">llvm::PreISelIntrinsicLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeupdatepass/#a1eef7e13ba8f6964ddd2f64c8a85d8b8">llvm::PseudoProbeUpdatePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/rellookuptableconverterpass/#a3b1519f165c877970b589c9f53db69eb">llvm::RelLookupTableConverterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#af56b6dd2da7f65fa682eaf6a16cdb36a">llvm::RewriteStatepointsForGC::run</a>, <a href="/web-llvm/docs/api/classes/llvm/safestackpass/#a7a84d5b29faf6a5ce458e61ac1f79cab">llvm::SafeStackPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileloaderpass/#a324d3696b255beea7cfd1e8b901b2363">llvm::SampleProfileLoaderPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a93d554aebdab8ad87f41ba8e07f73cad">llvm::SanitizerCoveragePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/selectoptimizepass/#acfc317afbeb9131cf40151f6227306cc">llvm::SelectOptimizePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/shadowstackgcloweringpass/#a2053b340bf34047264af3190e9473953">llvm::ShadowStackGCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/shouldnotrunfunctionpassesanalysis/#a658552d944fcee731a4843fcd616812b">llvm::ShouldNotRunFunctionPassesAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/shouldrunextrapasses/#a73cf5bc833ba6a5f5569836017de5ae8">llvm::ShouldRunExtraPasses&lt; MarkerTy &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siannotatecontrolflowpass/#a84e9204f8b261089c66706e2941ee6da">llvm::SIAnnotateControlFlowPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/siloadstoreoptimizerpass/#a73bd665c6e03c1dc196c107a450e228a">llvm::SILoadStoreOptimizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sjljehpreparepass/#a495925d0983e66d028a72e6b6748f072">llvm::SjLjEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ssplayoutanalysis/#a999c6653c5cd043b3398b180dbe43f07">llvm::SSPLayoutAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stackprotectorpass/#af99d23fe1a6d3d9ebfdf9fa3a101830a">llvm::StackProtectorPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalanalysis/#aa68230712fbc6c2839196d128777e5c5">llvm::StackSafetyGlobalAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltobitcodewriterpass/#a407be825a5084267d383681109e30df9">llvm::ThinLTOBitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/threadsanitizerpass/#a554dea073d38539bd97dbb495225a24b">llvm::ThreadSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/typesanitizerpass/#a2ffe7ab99b08300315a7ebb6e94ebbe4">llvm::TypeSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/uniformityinfoanalysis/#af8aad6f3b254e32f560836dd25a317a0">llvm::UniformityInfoAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/vectorcombinepass/#a6a1e4cac923bd64f58cb782f1a5ba91a">llvm::VectorCombinePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtpass/#af94d9399906155205bf6afa17427d5c7">llvm::WholeProgramDevirtPass::run</a>, <a href="/web-llvm/docs/api/structs/preservedcfgcheckeranalysis/#aabf037120a3d459531c28c262177ca99">PreservedCFGCheckerAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/preservedfunctionhashanalysis/#a59e9fb2b8fee32c19e4a94a9278fa150">PreservedFunctionHashAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/preservedmodulehashanalysis/#a2239a9867f123d10abc87905037eda1c">PreservedModuleHashAnalysis::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a804d6eb117c9b69c6b52f2655438e787">runCGProfilePass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a358b28b8ab641a2a22ed8849a2dff2cf">anonymous{SampleProfile.cpp}::SampleProfileLoader::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#abe3ea5f5ad2a17b7552318e8ffb3b0bb">anonymous{HWAddressSanitizer.cpp}::HWAddressSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoforcefunctionattrs-cpp/#a644a080a4331977e6930434b8eedb1d5">shouldRunOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineadvisoranalysis/result/#a64e2a53c670b4531950c994d84bc4e39">llvm::InlineAdvisorAnalysis::Result::tryCreate</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvice/#a19a31f34d91bfcdfa8c16f9a16079461">llvm::MLInlineAdvice::updateCachedCallerFPI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e739fb4907159062aacbbafea669592">llvm::updateCGAndAnalysisManagerForCGSCCPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a035e8c90cdcf756260ddd5ed0e9a26">llvm::updateCGAndAnalysisManagerForFunctionPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#ab31c9b14b5bd6245b789fb6ed28a7aeb">updateNewSCCFunctionAnalyses</a>.</p>

</div>
</div>

### Fun {#aec1db240440db5948a5f72be2665b8c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* Fun</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gaf31caae4259f8aaaac2d6cc296a3c952">LLVMRunPassesOnFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a137eaaa673e8fbf6bd1bfc41ea0c12b5">llvm::sys::RetryAfterSignal</a>.</p>

</div>
</div>

### LAM {#a7cfe61417446ebb812e81293bde22a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopAnalysisManager LAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#a4f45321972482ebcb5238a0bc72c3d55">crossRegisterProxies</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a3c2e12459e81e47a53dc49484af24bc2">llvm::PassBuilder::crossRegisterProxies</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonvectorloopcarriedreusepass/#a52ba23deb54308528d86b65258256a45">llvm::HexagonVectorLoopCarriedReusePass::HexagonVectorLoopCarriedReusePass</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#ae4d69467b6a430d145fd550952e2f4a8">llvm::LoopFlattenPass::LoopFlattenPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a32a8612a117894df2f1f35c72dce226e">llvm::PassBuilder::registerLoopAnalyses</a>, <a href="#a29bd660c45b6352afc9304125087acee">registerLoopAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonvectorloopcarriedreusepass/#a32948988705da5dd73dba608197477fc">llvm::HexagonVectorLoopCarriedReusePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopflattenpass/#af1670b8924fecfd8a7f0c4dc140bf603">llvm::LoopFlattenPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopunrollpass/#a62ed17cf8aa893362e6c3c1f6d8a0898">llvm::LoopUnrollPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a>.</p>

</div>
</div>

### LLVMErrorSuccess {#aa67bf7f2760d0e348e8c8f4546030f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">return LLVMErrorSuccess</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>

</div>
</div>

### Machine {#a2e16e55de32fe349f3e8242166918205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function const char TargetMachine* Machine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a41a194a45535dac693ad3d1d358cf200">llvm::jitlink::createLinkGraphFromCOFFObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a0194b0cf6c8e570555fe9a8eb0c8d167">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createShortImport</a>, <a href="/web-llvm/docs/api/classes/llvm/object/anonymous-coffimportfile-cpp-/objectfactory/#a3f315ec5e0d164d9cfc44a35fa8d0828">llvm::object::anonymous{COFFImportFile.cpp}::ObjectFactory::createWeakExternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e15236324209782fbeb6b5079e93a">llvm::dlltoolDriverMain</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a2cbe923c28eb9aa4603a52f98777986a">getCOFFFileMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a36f586048b3d4bb4f82bfd32f53a724a">llvm::object::getELFRelativeRelocationType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a26dff1f08cc67aef943d43c26f6d635a">llvm::object::getELFRelocationTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a506e41356e887f732b2edfb4bf0b4679">llvm::object::getELFSectionTypeName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a6c594664d7c57a587de68f6bae6d6aac">llvm::object::getImgRelRelocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aa602a35c5c3a61eab742f4956f1da643">llvm::jitlink::getMachineName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistream/#a25b67219b7075c2ffa3c3b0d94bffb48">llvm::pdb::DbiStream::getMachineType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#accca1ffcde97aed8658b3905915eb84c">llvm::object::getNameType</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile/#a18fe39da4c18a33b51c12a9efe787d62">llvm::pdb::PDBFile::getPointerSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#af09bd2faf3988ebd053e331ead3bd55d">llvm::ifs::initELFHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#acb6f88f4307d83ce7c625a0775f2b512">llvm::COFF::is64Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a4cdd8d73d6aba93a5790daaa2d767553">llvm::COFF::isAnyArm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#ad2af2071a60723ea6dd73bb28f238631">llvm::COFF::isArm64EC</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#a79cb02a6a30f77e1c1b4ef016c460a63">isValidReservedSectionIndex</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga9b0b2b1efd30fad999f2b2a7fdbf8492">LLVMCreateTargetMachine</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gae3e632706254c18142e979ad1aec63a9">LLVMRunPasses</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gaf31caae4259f8aaaac2d6cc296a3c952">LLVMRunPassesOnFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a3d857a172454acee51c2ee46b613ab26">llvm::pdb::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a2f6bbbb92fe0011da09fe978f0eb3d0d">llvm::object::parseCOFFModuleDefinition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dlltooldriver-cpp-/#ab4164a95af7321ce9ba5eca038e4cbfe">anonymous{DlltoolDriver.cpp}::parseModuleDefinition</a>, <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#af20152d720e6ffc7cf0151f2f657c3be">printWithoutType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af9d2c5b5d2afb86f9cdaef1946b79f6c">llvm::object::writeImportLibrary</a>.</p>

</div>
</div>

### MAM {#a85bddafa659a93a7a67c9094648259be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleAnalysisManager MAM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuopenclenqueuedblockloweringpass/#a888bed90ab690606a31b2de0a6529f42">llvm::AMDGPUOpenCLEnqueuedBlockLoweringPass::AMDGPUOpenCLEnqueuedBlockLoweringPass</a>, <a href="/web-llvm/docs/api/classes/llvm/gcfunctionanalysis/#a4f01110295958e03d88d7495198a40d6">llvm::GCFunctionAnalysis::AnalysisInfoMixin&lt; GCFunctionAnalysis &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/assignguidpass/#aea9d1c52a94e44bfae70ed8b19f4c709">llvm::AssignGUIDPass::AssignGUIDPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a52e95fe46f358afc3b0006f256f9d487">computeVirtualCallSiteTypeInfoMap</a>, <a href="#a4f45321972482ebcb5238a0bc72c3d55">crossRegisterProxies</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#a3c2e12459e81e47a53dc49484af24bc2">llvm::PassBuilder::crossRegisterProxies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a69cac14aa225532f4e20b4bbeae62c">llvm::getDefaultInlineOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc692529e90df46d42cb2a005ec02a95">llvm::getDevelopmentModeAdvisor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7acaa9d2987b3c0842cc1a758bfcb0d0">llvm::getInlineOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f5258dfed1ae5cd124270235c3b1055">llvm::getReleaseModeAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#aa6f227fc16925fab1dac5812dc6d0cd6">llvm::InlinerPass::InlinerPass</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#a721f6a9227830f0254a70a740f43f24f">llvm::MLInlineAdvisor::MLInlineAdvisor</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#adfb981cb8865a526a79cabb5e74d1034">llvm::ModuleInlinerPass::ModuleInlinerPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparser/#a20340b8661bf7b699e8948b1a8a81ced">llvm::MIRParser::parseMachineFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aff4be0d6e305b2b9b41970bc607c528c">llvm::MIRParserImpl::parseMachineFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofflatteningpass/#a6f12ffb4e62bf82dcba9f54405232d17">llvm::PGOCtxProfFlatteningPass::PGOCtxProfFlatteningPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofloweringpass/#a627aa6218c141f9b4c6c78dcb8115601">llvm::PGOCtxProfLoweringPass::PGOCtxProfLoweringPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pgomemopsizeopt/#a72252a50870f86f80ca78dc71d4d53ce">llvm::PGOMemOPSizeOpt::PGOMemOPSizeOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/indirectcallpromotion-cpp/#a42ff11c63c1a675d13cc97eaec48d621">promoteIndirectCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation/#ac08162972dd07f89c515c12aa05aa279">llvm::DebugifyEachInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedcfgcheckerinstrumentation/#aed649cf558f93dc41694657bc7f2442c">llvm::PreservedCFGCheckerInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/standardinstrumentations/#a0fa3fbf5294feb3ea1e34d89365de992">llvm::StandardInstrumentations::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/verifyinstrumentation/#abfec9362909844b463ec07ef82233199">llvm::VerifyInstrumentation::registerCallbacks</a>, <a href="#a8efe9e83ceb2ff61f7e6091fc8ebbe3c">registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/passbuilder/#acba45c16e3934023f1fe17627951b5b8">llvm::PassBuilder::registerModuleAnalyses</a>, <a href="#a3436adb2fa793c00b5cd18b99dd73c8b">registerModuleAnalyses</a>, <a href="/web-llvm/docs/api/classes/llvm/addresssanitizerpass/#a987afb1c68c5891e0b9a67cdac48147d">llvm::AddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/alwaysinlinerpass/#ac95b8d75e282ac5dbb2ed47ae1e1c88b">llvm::AlwaysInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuremoveincompatiblefunctionspass/#ac67b2b8b03c9e7cecf703fd30abb485e">llvm::AMDGPURemoveIncompatibleFunctionsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpusplitmodulepass/#a5fdf4ead69288861f3151e0f035a9877">llvm::AMDGPUSplitModulePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/assignguidpass/#aa89d9261590d9a6a45bb5a02e907c32c">llvm::AssignGUIDPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgprofilepass/#ab84e768b0ca66104a03d4dd6f96422fe">llvm::CGProfilePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/collectormetadataanalysis/#a940b13e06cb50e4d5b4ca391dc16e190">llvm::CollectorMetadataAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corocleanuppass/#ad94b3bcb5dea38b6b7d891fa9344322c">llvm::CoroCleanupPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a0cbc02f8988e793203b0a4f7e75587c0">llvm::CtxProfAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysisprinterpass/#a3edae17ead4808eee55b99b0e1add11b">llvm::CtxProfAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxiloplowering/#a8907c1ee9a102c2ec9a7895d352a7a6e">llvm::DXILOpLowering::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxilprettyprinterpass/#a80163db1be8afd66500bc24bb7275747">llvm::DXILPrettyPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/dxiltranslatemetadata/#a11fd26b2f007c308546f237ba5918bc5">llvm::DXILTranslateMetadata::run</a>, <a href="/web-llvm/docs/api/classes/llvm/eliminateavailableexternallypass/#acb30ee5db432a603141e0f783643f5d1">llvm::EliminateAvailableExternallyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaldcepass/#ae98558816f50b4a9f6f7244b2deadd53">llvm::GlobalDCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparacceleratorcodeselectionpass/#a3c59b50e60a44b5fa3871d0449aa4744">llvm::HipStdParAcceleratorCodeSelectionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hwaddresssanitizerpass/#a0ab6bbfe1dc498f2c9a8603d672fbb1b">llvm::HWAddressSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysis/#a987eec6d5acf850e47a52cc50ba9c7be">llvm::InlineAdvisorAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisoranalysisprinterpass/#ab6fd30da8bd8c6528e6bc9aa4c2f6633">llvm::InlineAdvisorAnalysisPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loweremutlspass/#aa02b6a6722504e6fb7a176a81fc5d49c">llvm::LowerEmuTLSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerwrapperpass/#a302bbe2963bced6cb8460b94f89dd0be">llvm::ModuleInlinerWrapperPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/modulethreadsanitizerpass/#adf10c75c773504153d27d41a73ad2223">llvm::ModuleThreadSanitizerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/numericalstabilitysanitizerpass/#aa05e97761e23096ba7621f0ad28c05ed">llvm::NumericalStabilitySanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofflatteningpass/#a13390fcce3ec8b52ef55488e967081c5">llvm::PGOCtxProfFlatteningPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofloweringpass/#a7ad703c2051de4321f9ef0d082a9c906">llvm::PGOCtxProfLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoindirectcallpromotion/#a5017234dfda3310cbcae123e5a4de31a">llvm::PGOIndirectCallPromotion::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgen/#a9cff4300652b1ae7f59c26011099ac65">llvm::PGOInstrumentationGen::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationgencreatevar/#a48fd4403aec933165941509e289a4938">llvm::PGOInstrumentationGenCreateVar::run</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoinstrumentationuse/#a11847c7e88a21b5076fb1cb5e2f7f5e1">llvm::PGOInstrumentationUse::run</a>, <a href="/web-llvm/docs/api/classes/llvm/plugininlineadvisoranalysis/#a9b307241d77fee693b65e68353a8d286">llvm::PluginInlineAdvisorAnalysis::run</a>, <a href="/web-llvm/docs/api/structs/llvm/realtimesanitizerpass/#a6ef2f34cb129c3b7d3a996e88f3e2c9e">llvm::RealtimeSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/sanitizercoveragepass/#a93d554aebdab8ad87f41ba8e07f73cad">llvm::SanitizerCoveragePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/shadowstackgcloweringpass/#a2053b340bf34047264af3190e9473953">llvm::ShadowStackGCLoweringPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/structuralhashprinterpass/#afe15599f186ed0311708ffe7f629d374">llvm::StructuralHashPrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/typesanitizerpass/#a2ffe7ab99b08300315a7ebb6e94ebbe4">llvm::TypeSanitizerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmapanalysis/#a01f5f291c2aa5b0c076173adeb2dbd3a">llvm::VirtRegMapAnalysis::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#ae1dadcf6ee688f96abb563274e620f44">llvm::AMDGPUTargetMachine::splitModule</a>.</p>

</div>
</div>

### Mod {#a4aca2bf0c649ae08d5627e350bb80eb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (auto Err = PB.parsePassPipeline(MPM, Passes)) return wrap(std MPM run* Mod</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpuinstprinter-cpp/#a26dc343a02d10198a652c221219dd321">allOpsDefaultValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a8aa3340974246e4e5e458129e1ecccd2">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::AMDGPUSwLowerLDS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a330a18768ffaafb198c726071dcfcb29">dropDeadSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a76d4e1301c34b44df3c6721266d5f38a">factorizeMinMaxTree</a>, <a href="/web-llvm/docs/api/classes/anonymous-sipeepholesdwa-cpp-/sdwasrcoperand/#a8c68256cc9ae18cd75c21521bc7f8c51">anonymous{SIPeepholeSDWA.cpp}::SDWASrcOperand::getSrcMods</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a388c19dd51467226753e433499a85e44">initAndLookupTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a722d17f2a55dcbd4743919cd6796d733">instCombineSVEAllActive</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#aafc1b31eca401e3ab7a3be9d8fdb697d">isEmptyModule</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantexpressions/#gaa025b4042992fcb4ee0a8495cebb32ba">LLVM_ATTRIBUTE_C_DEPRECATED</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga374a76b8284f82daa51c2ca3cb92ec26">LLVMGetFirstFunction</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga35ec32d09832c21269295c9686b3dfd5">LLVMGetFirstGlobal</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#gadfdd506e7f1b8ddc3dd4e734a10ee160">LLVMGetFirstGlobalAlias</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#gaca252d34e7d7aa26c80331144e9ef116">LLVMGetFirstGlobalIFunc</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gaf9a80c7e6b324262edc1ff545411ea26">LLVMGetFirstNamedMetadata</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#gae31cd442e48be38030a97c21a2c49867">LLVMGetIntrinsicDeclaration</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga78c26f83ae950f9b29cd108cf89557aa">LLVMGetLastFunction</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga51e947f836fac89e008e62a60ab8a0cc">LLVMGetLastGlobal</a>, <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#ga1bc4db1c43a056e814a130aa80ef551a">LLVMGetLastGlobalAlias</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#ga7c3f17cf17e29d05f5ff89939cae47aa">LLVMGetLastGlobalIFunc</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gab529111f5d4432548e3913d2d910e77c">LLVMGetLastNamedMetadata</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluefunction/#ga9537e3801e0a920c4af76a4360baa99b">LLVMIntrinsicCopyOverloadedName2</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga8575599668ea7c9ab24a07f284a3f5d8">LLVMRemoveModule</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gae3e632706254c18142e979ad1aec63a9">LLVMRunPasses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp/#a380dad8a77bc823770e1488a704ae8ca">LLVMTargetMachineEmit</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#aeec26ce8d8be46abb3008a9a8e6e9107">loadModuleFromInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#ac46926a2483bd793432d5ca0f7879de3">maybePrintCallAddrSpace</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mccodeemitter-cpp/#a624d914db11b33bdb836e37b51b9d2f5">modRMByte</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="#a10fde6bea2f819ef87db20d8fe3085c7">SI</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a2fad224b57541514de4fb5be6eb2e7f1">splitCodeGen</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobject-cpp/#ace9ca57da9b4fcd62a7db7e96bd75a73">toHexStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a6a3e2feaa7c55f28c3095ef8a747ae7d">transformCallee</a> and <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a35b932e3e318fc132ddc4eba034d9a12">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldImmWithOpSel</a>.</p>

</div>
</div>

### Passes {#a4a1f52f59d0b4cc188f43fbfdccf6c54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function const char* Passes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="#aabda80e998791549194f388227fc4481">if</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gae3e632706254c18142e979ad1aec63a9">LLVMRunPasses</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gaf31caae4259f8aaaac2d6cc296a3c952">LLVMRunPassesOnFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af16b5429cba93f00c53d5d4627725516">simplifySetCCWithCTPOP</a>.</p>

</div>
</div>

### PassOpts {#ae0a1ae95f374e415041f29efea8fee46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function const char TargetMachine LLVMPassBuilderOptions* PassOpts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  bool <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a> = PassOpts-&gt;DebugLogging
</div>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gae3e632706254c18142e979ad1aec63a9">LLVMRunPasses</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gaf31caae4259f8aaaac2d6cc296a3c952">LLVMRunPassesOnFunction</a> and <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

### PIC {#ad4d247df65c12507f447383be37d7ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PassInstrumentationCallbacks PIC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcntargetmachine/#a6b558554de041312d8c8cd3f1609c90c">llvm::GCNTargetMachine::buildCodeGenPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetmachine/#a00b4afd351da5d7ef32495bb1b790447">llvm::R600TargetMachine::buildCodeGenPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#abbcb807cb3ebda74ed9f56b456fc333e">llvm::X86TargetMachine::buildCodeGenPipeline</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a34b1bcd57f9c18a520b55819365ea9bb">llvm::Target::createMCObjectFileInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a70df8ac2134903deb0ab04be58e840f2">createRISCVMCObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#a2adec695334610982e70d013e958a4fd">llvm::TargetPassConfig::getStartStopInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a9ce8843410ce45dd5ca786651889b45b">llvm::MCObjectFileInfo::initMCObjectFileInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#a87b154d8853b7d1fa59b6ecf9b007820">anonymous{LICM.cpp}::LoopPromoter::LoopPromoter</a>, <a href="/web-llvm/docs/api/classes/llvm/timepasseshandler/#ac1d5878f935f77ce61e2d792797bd1e2">llvm::TimePassesHandler::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/timeprofilingpasseshandler/#a0974d93ee646e86089181c0fcc12da7b">llvm::TimeProfilingPassesHandler::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="#afd1501c49c84f3addfd108c2484f5674">PB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation/#ac08162972dd07f89c515c12aa05aa279">llvm::DebugifyEachInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a8561a3cb89ee3981d033ad4f4074bd07">llvm::DotCfgChangeReporter::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#a098ebeae73eb3b1c09384466602931e7">llvm::DroppedVariableStatsIR::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#a19c473cc925a0f73c964f7a7c12eeca3">llvm::InLineChangePrinter::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/irchangedprinter/#a6ab3f8cc3d69d55488725e41bad5e578">llvm::IRChangedPrinter::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/irchangedtester/#abb9ab16c8277ed4b633ce6560a1f4fb3">llvm::IRChangedTester::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/optnoneinstrumentation/#a13ae8310145a23455c25478da7fa8e39">llvm::OptNoneInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgateinstrumentation/#ab2b73a9eaecb02a4ec3beebaa431b972">llvm::OptPassGateInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedcfgcheckerinstrumentation/#aed649cf558f93dc41694657bc7f2442c">llvm::PreservedCFGCheckerInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/printcrashirinstrumentation/#af4e053aebd6ae8747dd34fbfc4c2ca47">llvm::PrintCrashIRInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/printpassinstrumentation/#a632f3dfe4f8043f8c6b50498ad7aba02">llvm::PrintPassInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeverifier/#a3c0c496c912a11733edef199e5ae5473">llvm::PseudoProbeVerifier::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/standardinstrumentations/#a0fa3fbf5294feb3ea1e34d89365de992">llvm::StandardInstrumentations::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/timepasseshandler/#a03d2e896dae596a26cf715589b8cf9f8">llvm::TimePassesHandler::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/timeprofilingpasseshandler/#a04ce26b9550579b73f15d79567dc8839">llvm::TimeProfilingPassesHandler::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/verifyinstrumentation/#abfec9362909844b463ec07ef82233199">llvm::VerifyInstrumentation::registerCallbacks</a>, <a href="#a8efe9e83ceb2ff61f7e6091fc8ebbe3c">registerCallbacks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a165bf75db00c7c146695f340487895fc">llvm::registerCodeGenCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#aa2fb31feeaf10f23b54a75e244c80035">llvm::ChangeReporter&lt; IRUnitT &gt;::registerRequiredCallbacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#a225705ff0411d7a7d1f5b72754ea8388">llvm::InLineChangePrinter::~InLineChangePrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/irchangedprinter/#a527c38a168e31fd5695da4b37784b876">llvm::IRChangedPrinter::~IRChangedPrinter</a>.</p>

</div>
</div>

### VerifyEach {#acf9a76b441b49648ba97e4a40c3ad5f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VerifyEach = <a href="#ae0a1ae95f374e415041f29efea8fee46">PassOpts</a>-&gt;VerifyEach</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp">PassBuilderBindings.cpp</a>.</p>


<p>Referenced by <a href="#ac80362d592aa56ce616f030fbc3a0bd0">if</a>, <a href="#aabda80e998791549194f388227fc4481">if</a>, <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#ga1f4b0b26dccab6bd18dc0461a4655758">LLVMPassBuilderOptionsSetVerifyEach</a> and <a href="#a10fde6bea2f819ef87db20d8fe3085c7">SI</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
