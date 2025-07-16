---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `SanitizerCoverage.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/instrumentation/sanitizercoverage-h">llvm/Transforms/Instrumentation/SanitizerCoverage.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/globalsmodref-h">llvm/Analysis/GlobalsModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/postdominators-h">llvm/Analysis/PostDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/dominators-h">llvm/IR/Dominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/ehpersonalities-h">llvm/IR/EHPersonalities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/mdbuilder-h">llvm/IR/MDBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/specialcaselist-h">llvm/Support/SpecialCaseList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/basicblockutils-h">llvm/Transforms/Utils/BasicBlockUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/moduleutils-h">llvm/Transforms/Utils/ModuleUtils.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-">anonymous{SanitizerCoverage.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage">ModuleSanitizerCoverage</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3ce3c416891376602062102e3f6086">isFullDominator</a> (const BasicBlock *BB, const DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a071735cb5607ce84acc51ba9a03962cb">isFullPostDominator</a> (const BasicBlock *BB, const PostDominatorTree &amp;PDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a> (const Function &amp;F, const BasicBlock *BB, const DominatorTree &amp;DT, const PostDominatorTree &amp;PDT, const SanitizerCoverageOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d87658bf2f69df81493401a7c6dc52">IsBackEdge</a> (BasicBlock *From, BasicBlock *To, const DominatorTree &amp;DT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9bf26831e594dfc27a349186a1c5822">IsInterestingCmp</a> (ICmpInst *CMP, const DominatorTree &amp;DT, const SanitizerCoverageOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4669da69bc647cbc2c6ce195b34f36">SanCovTracePCIndirName</a>[] = "__sanitizer_cov_trace_pc_indir"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e4c059ec99b6218c182b1574fcbd8a">SanCovTracePCName</a>[] = "__sanitizer_cov_trace_pc"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38f1c65c3525599ee83e57b75463ebd1">SanCovTraceCmp1</a>[] = "__sanitizer_cov_trace_cmp1"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc8f50a539e2e4e4abe594728c670cd">SanCovTraceCmp2</a>[] = "__sanitizer_cov_trace_cmp2"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63a7c660ceaaf868892d35c2f280559">SanCovTraceCmp4</a>[] = "__sanitizer_cov_trace_cmp4"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d730ef6fbded762b8e056ceec21dba">SanCovTraceCmp8</a>[] = "__sanitizer_cov_trace_cmp8"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a813298e826be69472cddee86a8f975c7">SanCovTraceConstCmp1</a>[] = "__sanitizer_cov_trace_const_cmp1"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802cd9d2e91474b5369c09ee34b9a969">SanCovTraceConstCmp2</a>[] = "__sanitizer_cov_trace_const_cmp2"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b379fc684f80f3704ef93e3c2511532">SanCovTraceConstCmp4</a>[] = "__sanitizer_cov_trace_const_cmp4"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c778fa4e1d70ca75766a57eba1622d9">SanCovTraceConstCmp8</a>[] = "__sanitizer_cov_trace_const_cmp8"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23c9c52fc5ba5b80f0ba5e9f445a3f7">SanCovLoad1</a>[] = "__sanitizer_cov_load1"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d39995945171c82827aac57b609496">SanCovLoad2</a>[] = "__sanitizer_cov_load2"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964a8a789ada569eb2d77e1448b00556">SanCovLoad4</a>[] = "__sanitizer_cov_load4"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323a2ec4205253d32835820dea38f001">SanCovLoad8</a>[] = "__sanitizer_cov_load8"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a625c71e7f07b74322842c8ba2f520d67">SanCovLoad16</a>[] = "__sanitizer_cov_load16"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d633a1a1de145d2888a394e4d33dc3">SanCovStore1</a>[] = "__sanitizer_cov_store1"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b4d8adcaa4a0e6ee7ca5771432e968">SanCovStore2</a>[] = "__sanitizer_cov_store2"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14ece56d32bbda978ab5c2367955be9">SanCovStore4</a>[] = "__sanitizer_cov_store4"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2d4c3cca15d25504808ad9c02a2d622">SanCovStore8</a>[] = "__sanitizer_cov_store8"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8b05cbc4494c7a61cecc6f83e00cfa5">SanCovStore16</a>[] = "__sanitizer_cov_store16"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ebecab3bbccc9fdd57f4db77a0e9bfd">SanCovTraceDiv4</a>[] = "__sanitizer_cov_trace_div4"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95def6f72117e9b44c137dba5aa8d7f7">SanCovTraceDiv8</a>[] = "__sanitizer_cov_trace_div8"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5695be293ad7d81a5cd76030a2055e">SanCovTraceGep</a>[] = "__sanitizer_cov_trace_gep"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38adaa9af5390a1e64c8fd0207e1963b">SanCovTraceSwitchName</a>[] = "__sanitizer_cov_trace_switch"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39a3eeade6f6668e57278d912c9071a4">SanCovModuleCtorTracePcGuardName</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa27cb010d7c5f282a819b2aa37aab3">SanCovModuleCtor8bitCountersName</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad208a7c19bcaa7810d6079ff9b0a372b">SanCovModuleCtorBoolFlagName</a>[] = "sancov.module_ctor_bool_flag"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f48a0c5e236f9c3dba145653d2e23c">SanCtorAndDtorPriority</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4429a97a75a264cec7fee0dabcfe673a">SanCovTracePCGuardName</a>[] = "__sanitizer_cov_trace_pc_guard"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbe4e5bb925ceeea30be3c33a7281cb">SanCovTracePCGuardInitName</a>[] = "__sanitizer_cov_trace_pc_guard_init"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c9d78b627349947124112474977f1d">SanCov8bitCountersInitName</a>[] = "__sanitizer_cov_8bit_counters_init"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56709052d5986f23318c4d13ce269166">SanCovBoolFlagInitName</a>[] = "__sanitizer_cov_bool_flag_init"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a438e6f841820a9536d96a24c3d91cf64">SanCovPCsInitName</a>[] = "__sanitizer_cov_pcs_init"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2785fd8dca205a2915dfa3ba3bf8ea6">SanCovCFsInitName</a>[] = "__sanitizer_cov_cfs_init"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d10fdcebd302c010ddb8b4923f7b410">SanCovGuardsSectionName</a>[] = "sancov_guards"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f6e16ce6987f6c7bb88a79a28f8aae7">SanCovCountersSectionName</a>[] = "sancov_cntrs"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb6e0753894ad3fe119c934f2eb9e39">SanCovBoolFlagSectionName</a>[] = "sancov_bools"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c59cb1bbdc19206ecaf120e457167b">SanCovPCsSectionName</a>[] = "sancov_pcs"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a055a5fdb0c33d76f1c0a33306c90aaec">SanCovCFsSectionName</a>[] = "sancov_cfs"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74ce28e7af43e45ba6730c32931a039">SanCovCallbackGateSectionName</a>[] = "sancov_gate"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c266d86a3587137724fe9c8d40b87a">SanCovLowestStackName</a>[] = "__sancov_lowest_stack"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9143a774df60b31a39ebcc08211a0225">SanCovCallbackGateName</a>[] = "__sancov_should_track"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a087e8fce1446a6c0f47996d66fb5883f">ClCoverageLevel</a>("sanitizer-coverage-level", cl::desc("Sanitizer Coverage. 0: none, 1: entry block, 2: all blocks, " "3: all blocks and critical edges"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa48daee972cdb91cc0749f31ca89eae7">ClTracePC</a>("sanitizer-coverage-trace-pc", cl::desc("Experimental pc tracing"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95896110981e827a9a6a943995e8c600">ClTracePCGuard</a>("sanitizer-coverage-trace-pc-guard", cl::desc("pc tracing with a guard"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42bcf9fefae825ca049233fc33561405">ClCreatePCTable</a>("sanitizer-coverage-pc-table", cl::desc("create a static PC table"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe6559fbc44f1ff3e08e466b891ace4">ClInline8bitCounters</a>("sanitizer-coverage-inline-8bit-counters", cl::desc("increments 8-bit counter for every edge"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ebc56bdf72b97446301ce4b8a3da7d">ClInlineBoolFlag</a>("sanitizer-coverage-inline-bool-flag", cl::desc("sets a boolean flag for every edge"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac078e1f43f3af7259e65cd9f8589426d">ClCMPTracing</a>("sanitizer-coverage-trace-compares", cl::desc("Tracing of CMP and similar instructions"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb75b19a8e0e6197cecf82daab10bf20">ClDIVTracing</a>("sanitizer-coverage-trace-divs", cl::desc("Tracing of DIV instructions"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03c575f46d699d5b0fa6d17896382e21">ClLoadTracing</a>("sanitizer-coverage-trace-loads", cl::desc("Tracing of load instructions"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1562d65b3653cbfcea640f097cff39">ClStoreTracing</a>("sanitizer-coverage-trace-stores", cl::desc("Tracing of store instructions"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98abe00eff5ce2fcbe03bdda7349d513">ClGEPTracing</a>("sanitizer-coverage-trace-geps", cl::desc("Tracing of GEP instructions"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa46a35f0a2abc392c67dfc56b9a6c40">ClPruneBlocks</a>("sanitizer-coverage-prune-blocks", cl::desc("Reduce the number of instrumented blocks"), cl::Hidden, cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd283a9e17437965355254fbe12065e">ClStackDepth</a>("sanitizer-coverage-stack-depth", cl::desc("max stack depth tracing"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc8e5eb0681178753ad8ff7a760c6ca">ClCollectCF</a>("sanitizer-coverage-control-flow", cl::desc("collect control flow for each function"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d736bf277e14e3b7f72c7165e4e03f6">ClGatedCallbacks</a>("sanitizer-coverage-gated-trace-callbacks", cl::desc("Gate the invocation of the tracing callbacks on a global variable" ". Currently only supported for trace-pc-guard and trace-cmp."), cl::Hidden, cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"sancov"</td>
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

### IsBackEdge() {#a82d87658bf2f69df81493401a7c6dc52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsBackEdge (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 613 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a57f1945911ca1e95d0f51d7c3516b529">llvm::BasicBlock::getUniqueSuccessor</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>.</p>


<p>Referenced by <a href="#ac9bf26831e594dfc27a349186a1c5822">IsInterestingCmp</a>.</p>

</div>
</div>

### isFullDominator() {#abc3ce3c416891376602062102e3f6086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFullDominator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT)</td>
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



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a126a78caf2176eb39d879c899bdd749c">llvm::succ_empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a26e2a938b431eaa6eca2beaa96410c9d">llvm::successors</a>.</p>


<p>Referenced by <a href="#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a>.</p>

</div>
</div>

### isFullPostDominator() {#a071735cb5607ce84acc51ba9a03962cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isFullPostDominator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp; PDT)</td>
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



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree/#ac74ec035b8eeaeb39cfea312fa876c75">llvm::PostDominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad66c4759666aab78529658362b498c74">llvm::pred_empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acb22fb04083152eee862457e42e8dc31">llvm::predecessors</a>.</p>


<p>Referenced by <a href="#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a>.</p>

</div>
</div>

### IsInterestingCmp() {#ac9bf26831e594dfc27a349186a1c5822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IsInterestingCmp (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> * CMP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a> &amp; Options)</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a82d87658bf2f69df81493401a7c6dc52">IsBackEdge</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### shouldInstrumentBlock() {#ad016e01a6a7d6f527043e7ded55dd65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldInstrumentBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/postdominatortree">PostDominatorTree</a> &amp; PDT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions">SanitizerCoverageOptions</a> &amp; Options)</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a0b4e7bee9b8575cc7db73329f1a561bd">llvm::BasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a161fd4e9fa5367f64c2a4c9e921c3ad3">llvm::BasicBlock::getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac24cd8d28904d8a4eac2dc3d7545355e">llvm::BasicBlock::getFirstNonPHIOrDbgOrLifetime</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a59fb91d1691350f7d1b8e8a114e3f2a4">llvm::BasicBlock::getSinglePredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abc3ce3c416891376602062102e3f6086">isFullDominator</a>, <a href="#a071735cb5607ce84acc51ba9a03962cb">isFullPostDominator</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/structs/llvm/sanitizercoverageoptions/#a6fbd9e46b04866c157520732aaaa99bea626aea6d83c51734a35fe969a0c86c5f">llvm::SanitizerCoverageOptions::SCK_Function</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ClCMPTracing {#ac078e1f43f3af7259e65cd9f8589426d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClCMPTracing("sanitizer-coverage-trace-compares", cl::desc("Tracing of CMP and similar instructions"), cl::Hidden)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClCollectCF {#a4dc8e5eb0681178753ad8ff7a760c6ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClCollectCF("sanitizer-coverage-control-flow", cl::desc("collect control flow for each function"), cl::Hidden)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClCoverageLevel {#a087e8fce1446a6c0f47996d66fb5883f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; ClCoverageLevel("sanitizer-coverage-level", cl::desc("Sanitizer Coverage. 0: none, 1: entry block, 2: all blocks, " "3: all blocks and critical edges"), cl::Hidden)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClCreatePCTable {#a42bcf9fefae825ca049233fc33561405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClCreatePCTable("sanitizer-coverage-pc-table", cl::desc("create a static PC table"), cl::Hidden)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClDIVTracing {#acb75b19a8e0e6197cecf82daab10bf20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClDIVTracing("sanitizer-coverage-trace-divs", cl::desc("Tracing of DIV instructions"), cl::Hidden)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClGatedCallbacks {#a5d736bf277e14e3b7f72c7165e4e03f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClGatedCallbacks("sanitizer-coverage-gated-trace-callbacks", cl::desc("Gate the invocation of the tracing callbacks on a global variable" ". Currently only supported for trace-pc-guard and trace-cmp."), cl::Hidden, cl::init(false))</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClGEPTracing {#a98abe00eff5ce2fcbe03bdda7349d513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClGEPTracing("sanitizer-coverage-trace-geps", cl::desc("Tracing of GEP instructions"), cl::Hidden)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClInline8bitCounters {#acbe6559fbc44f1ff3e08e466b891ace4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClInline8bitCounters("sanitizer-coverage-inline-8bit-counters", cl::desc("increments 8-bit counter for every edge"), cl::Hidden)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClInlineBoolFlag {#a18ebc56bdf72b97446301ce4b8a3da7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClInlineBoolFlag("sanitizer-coverage-inline-bool-flag", cl::desc("sets a boolean flag for every edge"), cl::Hidden)</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClLoadTracing {#a03c575f46d699d5b0fa6d17896382e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClLoadTracing("sanitizer-coverage-trace-loads", cl::desc("Tracing of load instructions"), cl::Hidden)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClPruneBlocks {#aaa46a35f0a2abc392c67dfc56b9a6c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClPruneBlocks("sanitizer-coverage-prune-blocks", cl::desc("Reduce the number of instrumented blocks"), cl::Hidden, cl::init(true))</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClStackDepth {#a0fd283a9e17437965355254fbe12065e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClStackDepth("sanitizer-coverage-stack-depth", cl::desc("max stack depth tracing"), cl::Hidden)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClStoreTracing {#a8e1562d65b3653cbfcea640f097cff39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClStoreTracing("sanitizer-coverage-trace-stores", cl::desc("Tracing of store instructions"), cl::Hidden)</td>
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



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClTracePC {#aa48daee972cdb91cc0749f31ca89eae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClTracePC("sanitizer-coverage-trace-pc", cl::desc("Experimental pc tracing"), cl::Hidden)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### ClTracePCGuard {#a95896110981e827a9a6a943995e8c600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ClTracePCGuard("sanitizer-coverage-trace-pc-guard", cl::desc("pc tracing with a guard"), cl::Hidden)</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizercoverage-cpp-/#ab9b8d17833329a87ee81549b43f366e7">anonymous{SanitizerCoverage.cpp}::OverrideFromCL</a>.</p>

</div>
</div>

### SanCov8bitCountersInitName {#a20c9d78b627349947124112474977f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCov8bitCountersInitName[] = "__sanitizer_cov_8bit_counters_init"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovBoolFlagInitName {#a56709052d5986f23318c4d13ce269166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovBoolFlagInitName[] = "__sanitizer_cov_bool_flag_init"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovBoolFlagSectionName {#a1cb6e0753894ad3fe119c934f2eb9e39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovBoolFlagSectionName[] = "sancov_bools"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovCallbackGateName {#a9143a774df60b31a39ebcc08211a0225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovCallbackGateName[] = "__sancov_should_track"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovCallbackGateSectionName {#ac74ce28e7af43e45ba6730c32931a039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovCallbackGateSectionName[] = "sancov_gate"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovCFsInitName {#aa2785fd8dca205a2915dfa3ba3bf8ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovCFsInitName[] = "__sanitizer_cov_cfs_init"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovCFsSectionName {#a055a5fdb0c33d76f1c0a33306c90aaec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovCFsSectionName[] = "sancov_cfs"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovCountersSectionName {#a3f6e16ce6987f6c7bb88a79a28f8aae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovCountersSectionName[] = "sancov_cntrs"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovGuardsSectionName {#a6d10fdcebd302c010ddb8b4923f7b410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovGuardsSectionName[] = "sancov_guards"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovLoad1 {#ab23c9c52fc5ba5b80f0ba5e9f445a3f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovLoad1[] = "__sanitizer_cov_load1"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovLoad16 {#a625c71e7f07b74322842c8ba2f520d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovLoad16[] = "__sanitizer_cov_load16"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovLoad2 {#af3d39995945171c82827aac57b609496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovLoad2[] = "__sanitizer_cov_load2"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovLoad4 {#a964a8a789ada569eb2d77e1448b00556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovLoad4[] = "__sanitizer_cov_load4"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovLoad8 {#a323a2ec4205253d32835820dea38f001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovLoad8[] = "__sanitizer_cov_load8"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovLowestStackName {#af7c266d86a3587137724fe9c8d40b87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovLowestStackName[] = "__sancov_lowest_stack"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovModuleCtor8bitCountersName {#a4aa27cb010d7c5f282a819b2aa37aab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovModuleCtor8bitCountersName[]</td>
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
<div class="doxyVerbatim">=
    "sancov.module_ctor_8bit_counters"
</div>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovModuleCtorBoolFlagName {#ad208a7c19bcaa7810d6079ff9b0a372b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovModuleCtorBoolFlagName[] = "sancov.module_ctor_bool_flag"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovModuleCtorTracePcGuardName {#a39a3eeade6f6668e57278d912c9071a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovModuleCtorTracePcGuardName[]</td>
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
<div class="doxyVerbatim">=
    "sancov.module_ctor_trace_pc_guard"
</div>
</dd>
</dl>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovPCsInitName {#a438e6f841820a9536d96a24c3d91cf64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovPCsInitName[] = "__sanitizer_cov_pcs_init"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovPCsSectionName {#ab0c59cb1bbdc19206ecaf120e457167b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovPCsSectionName[] = "sancov_pcs"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovStore1 {#a79d633a1a1de145d2888a394e4d33dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovStore1[] = "__sanitizer_cov_store1"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovStore16 {#ac8b05cbc4494c7a61cecc6f83e00cfa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovStore16[] = "__sanitizer_cov_store16"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovStore2 {#aa8b4d8adcaa4a0e6ee7ca5771432e968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovStore2[] = "__sanitizer_cov_store2"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovStore4 {#af14ece56d32bbda978ab5c2367955be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovStore4[] = "__sanitizer_cov_store4"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovStore8 {#ae2d4c3cca15d25504808ad9c02a2d622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovStore8[] = "__sanitizer_cov_store8"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceCmp1 {#a38f1c65c3525599ee83e57b75463ebd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceCmp1[] = "__sanitizer_cov_trace_cmp1"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceCmp2 {#adfc8f50a539e2e4e4abe594728c670cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceCmp2[] = "__sanitizer_cov_trace_cmp2"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceCmp4 {#af63a7c660ceaaf868892d35c2f280559}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceCmp4[] = "__sanitizer_cov_trace_cmp4"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceCmp8 {#ac0d730ef6fbded762b8e056ceec21dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceCmp8[] = "__sanitizer_cov_trace_cmp8"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceConstCmp1 {#a813298e826be69472cddee86a8f975c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceConstCmp1[] = "__sanitizer_cov_trace_const_cmp1"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceConstCmp2 {#a802cd9d2e91474b5369c09ee34b9a969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceConstCmp2[] = "__sanitizer_cov_trace_const_cmp2"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceConstCmp4 {#a1b379fc684f80f3704ef93e3c2511532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceConstCmp4[] = "__sanitizer_cov_trace_const_cmp4"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceConstCmp8 {#a6c778fa4e1d70ca75766a57eba1622d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceConstCmp8[] = "__sanitizer_cov_trace_const_cmp8"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceDiv4 {#a4ebecab3bbccc9fdd57f4db77a0e9bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceDiv4[] = "__sanitizer_cov_trace_div4"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceDiv8 {#a95def6f72117e9b44c137dba5aa8d7f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceDiv8[] = "__sanitizer_cov_trace_div8"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceGep {#a5f5695be293ad7d81a5cd76030a2055e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceGep[] = "__sanitizer_cov_trace_gep"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTracePCGuardInitName {#a4dbe4e5bb925ceeea30be3c33a7281cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTracePCGuardInitName[] = "__sanitizer_cov_trace_pc_guard_init"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTracePCGuardName {#a4429a97a75a264cec7fee0dabcfe673a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTracePCGuardName[] = "__sanitizer_cov_trace_pc_guard"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTracePCIndirName {#afe4669da69bc647cbc2c6ce195b34f36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTracePCIndirName[] = "__sanitizer_cov_trace_pc_indir"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTracePCName {#ae4e4c059ec99b6218c182b1574fcbd8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTracePCName[] = "__sanitizer_cov_trace_pc"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCovTraceSwitchName {#a38adaa9af5390a1e64c8fd0207e1963b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char SanCovTraceSwitchName[] = "__sanitizer_cov_trace_switch"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>.</p>

</div>
</div>

### SanCtorAndDtorPriority {#a55f48a0c5e236f9c3dba145653d2e23c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t SanCtorAndDtorPriority = 2</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"sancov"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp">SanitizerCoverage.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
