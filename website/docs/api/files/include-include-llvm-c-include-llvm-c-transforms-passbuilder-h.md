---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/include/llvm-c/transforms/passbuilder-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `PassBuilder.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">llvm-c/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/targetmachine-h">llvm-c/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">typedefLLVM_C_EXTERN_C_BEGIN struct LLVMOpaquePassBuilderOptions * <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gab96a23e2cec5c8e689f952c7c9daadb9">LLVMPassBuilderOptionsRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A set of options passed which are attached to the Pass Manager upon run. <a href="/web-llvm/docs/api/groups/llvmccorenewpm/#gab96a23e2cec5c8e689f952c7c9daadb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

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


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
