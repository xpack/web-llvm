---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/targetmachinec-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TargetMachineC.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">llvm-c/Core.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/targetmachine-h">llvm-c/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/legacypassmanager-h">llvm/IR/LegacyPassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/cbindingwrapping-h">llvm/Support/CBindingWrapping.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/codegencwrappers-h">llvm/Target/CodeGenCWrappers.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/host-h">llvm/TargetParser/Host.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/subtargetfeature-h">llvm/TargetParser/SubtargetFeature.h</a>"
#include &lt;cstring&gt;
#include &lt;optional&gt;
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/llvmtargetmachineoptions">LLVMTargetMachineOptions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Options for <a href="/web-llvm/docs/api/groups/llvmctarget/#ga9b0b2b1efd30fad999f2b2a7fdbf8492">LLVMCreateTargetMachine()</a>. <a href="/web-llvm/docs/api/structs/llvm/llvmtargetmachineoptions/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e9e5d11fbb7f3338160da224abc7bd">DEFINE_SIMPLE_CONVERSION_FUNCTIONS</a> (LLVMTargetMachineOptions, LLVMTargetMachineOptionsRef) static TargetMachine *unwrap(LLVMTargetMachineRef P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd76fc844321da09f76f721337742674">unwrap</a> (LLVMTargetRef P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fe4041db3281600b33fbb1bde23f0d2">wrap</a> (const TargetMachine *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmctarget/#ga1ec4bda112ca57f7eb2ac766ce0ca54f">LLVMTargetRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee50326c04a92d4d635d8846a866057">wrap</a> (const Target *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a380dad8a77bc823770e1488a704ae8ca">LLVMTargetMachineEmit</a> (LLVMTargetMachineRef T, LLVMModuleRef M, raw_pwrite_stream &amp;OS, LLVMCodeGenFileType codegen, char **ErrorMessage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga1ec4bda112ca57f7eb2ac766ce0ca54f">LLVMTargetRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga14fa4ed2b3cf4ff0012d7598e66e89ec">LLVMGetFirstTarget</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the first <a href="/web-llvm/docs/api/classes/llvm/target">llvm::Target</a> in the registered targets list. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga14fa4ed2b3cf4ff0012d7598e66e89ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga1ec4bda112ca57f7eb2ac766ce0ca54f">LLVMTargetRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaa8215937be9eb3154289503b1fe64f7f">LLVMGetNextTarget</a> (LLVMTargetRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the next <a href="/web-llvm/docs/api/classes/llvm/target">llvm::Target</a> given a previous one (or null if there's none) <a href="/web-llvm/docs/api/groups/llvmctarget/#gaa8215937be9eb3154289503b1fe64f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga1ec4bda112ca57f7eb2ac766ce0ca54f">LLVMTargetRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga57bc27c27706c0ee7a36152ff7f65a56">LLVMGetTargetFromName</a> (const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the target corresponding to the given name and stores it in <span class="doxyComputerOutput">T</span>. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga57bc27c27706c0ee7a36152ff7f65a56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga7a746a65818e0b6bd86e5f00a568e301">LLVMGetTargetFromTriple</a> (const char *Triple, LLVMTargetRef *T, char **ErrorMessage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the target corresponding to the given triple and stores it in <span class="doxyComputerOutput">T</span>. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga7a746a65818e0b6bd86e5f00a568e301">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga4235a7651c1b9c6d4ce651d3d5d4c3a2">LLVMGetTargetName</a> (LLVMTargetRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the name of a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga4235a7651c1b9c6d4ce651d3d5d4c3a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga62bdb1f3f956c85c862f8fbeb20fd374">LLVMGetTargetDescription</a> (LLVMTargetRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the description of a target. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga62bdb1f3f956c85c862f8fbeb20fd374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaec1fe38b8441da7e07adc844a2ef844e">LLVMTargetHasJIT</a> (LLVMTargetRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if the target has a JIT. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaec1fe38b8441da7e07adc844a2ef844e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gac3929c90f2c8e34da1950444159997c7">LLVMTargetHasTargetMachine</a> (LLVMTargetRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if the target has a TargetMachine associated. <a href="/web-llvm/docs/api/groups/llvmctarget/#gac3929c90f2c8e34da1950444159997c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga87cdf0ec25b92a6d3328976b2d782a1b">LLVMTargetHasAsmBackend</a> (LLVMTargetRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns if the target as an ASM backend (required for emitting output) <a href="/web-llvm/docs/api/groups/llvmctarget/#ga87cdf0ec25b92a6d3328976b2d782a1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga452c55a68775eff947a6efbebe1264b4">LLVMTargetMachineOptionsRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga779c6f18d39f1e9b447685c6748b714c">LLVMCreateTargetMachineOptions</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new set of options for an <a href="/web-llvm/docs/api/classes/llvm/targetmachine">llvm::TargetMachine</a>. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga779c6f18d39f1e9b447685c6748b714c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga407db5681cad54708f977c5e67db38d1">LLVMDisposeTargetMachineOptions</a> (LLVMTargetMachineOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an <a href="/web-llvm/docs/api/groups/llvmctarget/#ga452c55a68775eff947a6efbebe1264b4">LLVMTargetMachineOptionsRef</a> instance. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga407db5681cad54708f977c5e67db38d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga05e77be97655f8f0bd72c1b66b495025">LLVMTargetMachineOptionsSetCPU</a> (LLVMTargetMachineOptionsRef Options, const char *CPU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga060ae99cd61ea2256ee17c3efb005a82">LLVMTargetMachineOptionsSetFeatures</a> (LLVMTargetMachineOptionsRef Options, const char *Features)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the list of features for the target machine. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga060ae99cd61ea2256ee17c3efb005a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaa25c3b17c1c5c4f68e634e9a8951c306">LLVMTargetMachineOptionsSetABI</a> (LLVMTargetMachineOptionsRef Options, const char *ABI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga3599f27485335a91cdcd4f3aa637dc4d">LLVMTargetMachineOptionsSetCodeGenOptLevel</a> (LLVMTargetMachineOptionsRef Options, LLVMCodeGenOptLevel Level)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga129f96a5933437a275a3cbd2e103200a">LLVMTargetMachineOptionsSetRelocMode</a> (LLVMTargetMachineOptionsRef Options, LLVMRelocMode Reloc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gae0093d6c8da4828b8c70d5c5f3f59da9">LLVMTargetMachineOptionsSetCodeModel</a> (LLVMTargetMachineOptionsRef Options, LLVMCodeModel CodeModel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gad5c3bf4cc627842e1987abae68f676de">LLVMCreateTargetMachineWithOptions</a> (LLVMTargetRef T, const char *Triple, LLVMTargetMachineOptionsRef Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new <a href="/web-llvm/docs/api/classes/llvm/targetmachine">llvm::TargetMachine</a>. <a href="/web-llvm/docs/api/groups/llvmctarget/#gad5c3bf4cc627842e1987abae68f676de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga9b0b2b1efd30fad999f2b2a7fdbf8492">LLVMCreateTargetMachine</a> (LLVMTargetRef T, const char *Triple, const char *CPU, const char *Features, LLVMCodeGenOptLevel Level, LLVMRelocMode Reloc, LLVMCodeModel CodeModel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new <a href="/web-llvm/docs/api/classes/llvm/targetmachine">llvm::TargetMachine</a>. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga9b0b2b1efd30fad999f2b2a7fdbf8492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaeb0530e3fb06ccd5427d4aae90343e69">LLVMDisposeTargetMachine</a> (LLVMTargetMachineRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose the <a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a> instance generated by LLVMCreateTargetMachine. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaeb0530e3fb06ccd5427d4aae90343e69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga1ec4bda112ca57f7eb2ac766ce0ca54f">LLVMTargetRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gad7f62fd5370aa85da5e0dee443460c81">LLVMGetTargetMachineTarget</a> (LLVMTargetMachineRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Target used in a TargetMachine. <a href="/web-llvm/docs/api/groups/llvmctarget/#gad7f62fd5370aa85da5e0dee443460c81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga92fd190a62cd7cf6f6152750520b0843">LLVMGetTargetMachineTriple</a> (LLVMTargetMachineRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the triple used creating this target machine. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga92fd190a62cd7cf6f6152750520b0843">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga37bc632cea9c2707e6eebe0ec0c29f93">LLVMGetTargetMachineCPU</a> (LLVMTargetMachineRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the cpu used creating this target machine. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga37bc632cea9c2707e6eebe0ec0c29f93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaf834ba853e73fa2be1ef63c36f89fc67">LLVMGetTargetMachineFeatureString</a> (LLVMTargetMachineRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the feature string used creating this target machine. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaf834ba853e73fa2be1ef63c36f89fc67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga6ff2e8e833b72fbf37a3369de4cf7381">LLVMSetTargetMachineAsmVerbosity</a> (LLVMTargetMachineRef T, LLVMBool VerboseAsm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target machine's ASM verbosity. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga6ff2e8e833b72fbf37a3369de4cf7381">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga60acf4afa148289522ebfa6c96c11556">LLVMSetTargetMachineFastISel</a> (LLVMTargetMachineRef T, LLVMBool Enable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable fast-path instruction selection. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga60acf4afa148289522ebfa6c96c11556">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga518c16593c362630ee5a00db4a6ca0ed">LLVMSetTargetMachineGlobalISel</a> (LLVMTargetMachineRef T, LLVMBool Enable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable global instruction selection. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga518c16593c362630ee5a00db4a6ca0ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gae6639bf7d67999ecdf8a81cf44e9c22e">LLVMSetTargetMachineGlobalISelAbort</a> (LLVMTargetMachineRef T, LLVMGlobalISelAbortMode Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set abort behaviour when global instruction selection fails to lower/select an instruction. <a href="/web-llvm/docs/api/groups/llvmctarget/#gae6639bf7d67999ecdf8a81cf44e9c22e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga10cdcd226b050eb8902f3193039c1497">LLVMSetTargetMachineMachineOutliner</a> (LLVMTargetMachineRef T, LLVMBool Enable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable the MachineOutliner pass. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga10cdcd226b050eb8902f3193039c1497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gace7868f675950a8dfc3338b14652c686">LLVMTargetDataRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gabf046e92b04f6530ebdc64f95f77cbad">LLVMCreateTargetDataLayout</a> (LLVMTargetMachineRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a DataLayout based on the targetMachine. <a href="/web-llvm/docs/api/groups/llvmctarget/#gabf046e92b04f6530ebdc64f95f77cbad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga8d5be4abc46b15b48cebc50bdbcf219b">LLVMTargetMachineEmitToFile</a> (LLVMTargetMachineRef T, LLVMModuleRef M, const char *Filename, LLVMCodeGenFileType codegen, char **ErrorMessage)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emits an asm or object file for the given module to the filename. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga8d5be4abc46b15b48cebc50bdbcf219b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#gaaa9ce583969eb8754512e70ec4b80061">LLVMTargetMachineEmitToMemoryBuffer</a> (LLVMTargetMachineRef T, LLVMModuleRef M, LLVMCodeGenFileType codegen, char **ErrorMessage, LLVMMemoryBufferRef *OutMemBuf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compile the LLVM IR stored in <span class="doxyComputerOutput">M</span> and store the result in <span class="doxyComputerOutput">OutMemBuf</span>. <a href="/web-llvm/docs/api/groups/llvmctarget/#gaaa9ce583969eb8754512e70ec4b80061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga6b1d461077ad6a312eeaa2f0d561002e">LLVMGetDefaultTargetTriple</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a triple for the host machine as a string. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga6b1d461077ad6a312eeaa2f0d561002e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga7ea7895c81baccbdbccc5a6bb8be4fb3">LLVMNormalizeTargetTriple</a> (const char *triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Normalize a target triple. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga7ea7895c81baccbdbccc5a6bb8be4fb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga2350c332ed29d2aa178ce014d01e9d1e">LLVMGetHostCPUName</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the host CPU as a string. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga2350c332ed29d2aa178ce014d01e9d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga1186db08841661c3349d23a4344edd38">LLVMGetHostCPUFeatures</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the host CPU's features as a string. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga1186db08841661c3349d23a4344edd38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmctarget/#ga5624a39395aa46f764763fa169618c73">LLVMAddAnalysisPasses</a> (LLVMTargetMachineRef T, LLVMPassManagerRef PM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the target-specific analysis passes to the pass manager. <a href="/web-llvm/docs/api/groups/llvmctarget/#ga5624a39395aa46f764763fa169618c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### DEFINE\_SIMPLE\_CONVERSION\_FUNCTIONS() {#a23e9e5d11fbb7f3338160da224abc7bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEFINE_SIMPLE_CONVERSION_FUNCTIONS (<a href="/web-llvm/docs/api/structs/llvm/llvmtargetmachineoptions">LLVMTargetMachineOptions</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga452c55a68775eff947a6efbebe1264b4">LLVMTargetMachineOptionsRef</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp">TargetMachineC.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### LLVMTargetMachineEmit() {#a380dad8a77bc823770e1488a704ae8ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMTargetMachineEmit (<a href="/web-llvm/docs/api/groups/llvmctarget/#ga2fd34441d1fdf9466981c6c95caea314">LLVMTargetMachineRef</a> T, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gad1d1bb5f901c903a0cf09c5a053c9c56">LLVMModuleRef</a> M, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a> &amp; OS, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga001bfa8b65c06272b3449a256c961487">LLVMCodeGenFileType</a> codegen, char ** ErrorMessage)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp">TargetMachineC.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260acb99c054b7e0e1eaaabe4deee41e5945">llvm::AssemblyFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#gga001bfa8b65c06272b3449a256c961487aa9f8e1d866a4af34adc113280068a9df">LLVMAssemblyFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260a95aca07e95d9459c1bb31f4e7f9fda10">llvm::ObjectFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab1172d7b7736569e908ce727bfb3e358">pass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmctarget/#ga8d5be4abc46b15b48cebc50bdbcf219b">LLVMTargetMachineEmitToFile</a> and <a href="/web-llvm/docs/api/groups/llvmctarget/#gaaa9ce583969eb8754512e70ec4b80061">LLVMTargetMachineEmitToMemoryBuffer</a>.</p>

</div>
</div>

### unwrap() {#abd76fc844321da09f76f721337742674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Target * unwrap (<a href="/web-llvm/docs/api/groups/llvmctarget/#ga1ec4bda112ca57f7eb2ac766ce0ca54f">LLVMTargetRef</a> P)</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp">TargetMachineC.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### wrap() {#a5fe4041db3281600b33fbb1bde23f0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTargetMachineRef wrap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * P)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp">TargetMachineC.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

### wrap() {#a1ee50326c04a92d4d635d8846a866057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMTargetRef wrap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> * P)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp">TargetMachineC.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
