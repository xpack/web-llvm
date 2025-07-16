---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARMTargetMachine.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/arm-h">ARM.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlatencymutations-h">ARMLatencyMutations.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmacrofusion-h">ARMMacroFusion.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-h">ARMSubtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetobjectfile-h">ARMTargetObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-h">ARMTargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-h">MCTargetDesc/ARMMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/targetinfo/armtargetinfo-h">TargetInfo/ARMTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">llvm/CodeGen/ExecutionDomainFix.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/irtranslator-h">llvm/CodeGen/GlobalISel/IRTranslator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselect-h">llvm/CodeGen/GlobalISel/InstructionSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizer-h">llvm/CodeGen/GlobalISel/Legalizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">llvm/CodeGen/GlobalISel/LegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">llvm/CodeGen/MIRParser/MIParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetloweringobjectfile-h">llvm/Target/TargetLoweringObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/armtargetparser-h">llvm/TargetParser/ARMTargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/targetparser-h">llvm/TargetParser/TargetParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/cfguard-h">llvm/Transforms/CFGuard.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include &lt;cassert&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-armtargetmachine-cpp-">anonymous{ARMTargetMachine.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig">ARMPassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armexecutiondomainfix">ARMExecutionDomainFix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6685488f57ab6c8880f8e18a5364181a">LLVMInitializeARMTarget</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3bdb2a4dc7856d907dd29807c6545e2">createTLOF</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102">ARMBaseTargetMachine::ARMABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725fe8674a09b1579039321d641118e4">computeTargetABI</a> (const Triple &amp;TT, StringRef CPU, const TargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb29b487708f0dc2a940345b68649270">computeDataLayout</a> (const Triple &amp;TT, StringRef CPU, const TargetOptions &amp;Options, bool isLittle)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd00168ff221265f6b419664beff054">getEffectiveRelocModel</a> (const Triple &amp;TT, std::optional&lt; Reloc::Model &gt; RM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f604a8df9eb00990e08e7a415da25e6">INITIALIZE_PASS_BEGIN</a> (ARMExecutionDomainFix, "arm-execution-domain-fix", "ARM Execution Domain Fix", false, false) INITIALIZE_PASS_END(ARMExecutionDomainFix</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185f796e4f7cd1e63eb45389733b7315">DisableA15SDOptimization</a>("disable-a15-sd-optimization", cl::Hidden, cl::desc("Inhibit optimization of S->D register accesses on A15"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abae136d266feeb904096250bd5815fa2">EnableAtomicTidy</a>("arm-atomic-cfg-tidy", cl::Hidden, cl::desc("Run SimplifyCFG after expanding atomic operations" " to make use of cmpxchg flow-based information"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab229c5cdee13db12e0693b0e376c5feb">EnableARMLoadStoreOpt</a>("arm-load-store-opt", cl::Hidden, cl::desc("Enable ARM load/store optimization pass"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fad0b7377c229d2a3de9d17a23990ec">EnableGlobalMerge</a>("arm-global-merge", cl::Hidden, cl::desc("Enable the global merge pass"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">arm <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#ab3dc29e58ba69d53069ae504c20e1f1a">execution</a> domain</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86b29362e5d8fbb0d516610e4f988b5e">fix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">arm <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#ab3dc29e58ba69d53069ae504c20e1f1a">execution</a> domain ARM Execution <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364a3b69961cc13645dcabbe454f3309">Fix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">arm <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#ab3dc29e58ba69d53069ae504c20e1f1a">execution</a> domain ARM Execution <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc54b2f9f03c972ad8ae1c851533f1d1">false</a></td>
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

### computeDataLayout() {#adb29b487708f0dc2a940345b68649270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string computeDataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, bool isLittle)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a686afcd1d06fbc117abe52c54c5a3798">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102af871cdc1efbb58999dd6b201aeb9f28a">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS16</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a7424602c00cf8320e081c29111bdeef7">llvm::ARMBaseTargetMachine::ARM_ABI_APCS</a>, <a href="#a725fe8674a09b1579039321d641118e4">computeTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a1c5b48c01700ee5c1d1a6df0fec2c72e">llvm::DataLayout::getManglingComponent</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### computeTargetABI() {#a725fe8674a09b1579039321d641118e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMBaseTargetMachine::ARMABI computeTargetABI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a686afcd1d06fbc117abe52c54c5a3798">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102af871cdc1efbb58999dd6b201aeb9f28a">llvm::ARMBaseTargetMachine::ARM_ABI_AAPCS16</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a7424602c00cf8320e081c29111bdeef7">llvm::ARMBaseTargetMachine::ARM_ABI_APCS</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#a35fea9990d0205966c516f00e0f84102a5db5a8ac18cb47ad6f78ed8b3694b462">llvm::ARMBaseTargetMachine::ARM_ABI_UNKNOWN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a2033c9c8bb35857028fedf2f53ffb6de">llvm::ARM::computeDefaultTargetABI</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="#adb29b487708f0dc2a940345b68649270">computeDataLayout</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsasmparser/#a96cded7294d54537fbb8eb5a6148448a">anonymous{MipsAsmParser.cpp}::MipsAsmParser::MipsAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#a9329650dea81789565d4d4e7019c81eb">llvm::PPCTargetMachine::PPCTargetMachine</a>.</p>

</div>
</div>

### createTLOF() {#af3bdb2a4dc7856d907dd29807c6545e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TargetLoweringObjectFile &gt; createTLOF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

### getEffectiveRelocModel() {#adbd00168ff221265f6b419664beff054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model getEffectiveRelocModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a455bffdcf9dfc03e4b8f11c6085d0f3e">llvm::Reloc::DynamicNoPIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a5580e4c06cf7c1cc2d1c2ef00534ac17">llvm::Reloc::ROPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a593b80c5ddf9a5f0c06860e6711955d5">llvm::Reloc::ROPI_RWPI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a33108d181242a6b5c92f1bdb81d38128">llvm::Reloc::RWPI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a4f604a8df9eb00990e08e7a415da25e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (ARMExecutionDomainFix, "arm-<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/speculativeexecution-cpp/#ab3dc29e58ba69d53069ae504c20e1f1a">execution</a>-domain-fix", "ARM Execution <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad75d6f4f14a7b791076c6785aa59be4">Domain</a> Fix", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### LLVMInitializeARMTarget() {#a6685488f57ab6c8880f8e18a5364181a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeARMTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbdfccf3485b9df9d34a6dea50800f15">llvm::getTheARMBETarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae5953c94ed91f0f067547dc772cd80fe">llvm::getTheARMLETarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cec3961e7261d3cbcaa20409f1290c6">llvm::getTheThumbBETarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc701aa0872cfd76352f3bd7695834bb">llvm::getTheThumbLETarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7dde9e709ab3ef08973d0d6929071ca">llvm::initializeARMBlockPlacementPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71a253df2a9e8fdef117225bd6d3d56f">llvm::initializeARMBranchTargetsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a07c7e0efa31fe3636c04315149a824d0">llvm::initializeARMConstantIslandsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee05f527166ead9ff5f9c7e9eb0b41e4">llvm::initializeARMDAGToDAGISelLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac468512674ddb3d20d5aa9ed10569c16">llvm::initializeARMExecutionDomainFixPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9189f391832286ac8b52b0f6cc479c5f">llvm::initializeARMExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9e84933d6777aad61ac73ec02256798">llvm::initializeARMFixCortexA57AES1742098Pass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af2beb619cd5c5b4b1f518e6d21f36566">llvm::initializeARMLoadStoreOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abb117d5a135d66cdf1437bd22f6a2f5d">llvm::initializeARMLowOverheadLoopsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d09778af346d6e981fa54daf7f98d71">llvm::initializeARMParallelDSPPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7da5520e1937b21fa5758952ab7677f">llvm::initializeARMPreAllocLoadStoreOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9dc07f2e3d2bb069cf8ba0e9b471f41b">llvm::initializeARMSLSHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa096f48562c0dd3a59ef81dd9126239a">llvm::initializeGlobalISel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad01d5e31fa9109df49f57e1e5e5a45f7">llvm::initializeMVEGatherScatterLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29b5f9c1e822e79ab45d163d9fb871ea">llvm::initializeMVELaneInterleavingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25a558c9ffeac80ca80dddeac8927857">llvm::initializeMVETailPredicationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac444647c8fade507b99c503f93b7fb1e">llvm::initializeMVETPAndVPTOptimisationsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeb49c3df84382936601a6eab892775c7">llvm::initializeMVEVPTBlockPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc836a8c5d08a8975d808d831ba10c25">llvm::initializeThumb2SizeReducePass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableA15SDOptimization {#a185f796e4f7cd1e63eb45389733b7315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableA15SDOptimization("disable-a15-sd-optimization", cl::Hidden, cl::desc("Inhibit optimization of S-&gt;D register accesses on A15"), cl::init(false))</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a05892747560afe9409036ecccb3474a3">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableARMLoadStoreOpt {#ab229c5cdee13db12e0693b0e376c5feb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableARMLoadStoreOpt("arm-load-store-opt", cl::Hidden, cl::desc("Enable ARM load/store optimization pass"), cl::init(true))</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a05892747560afe9409036ecccb3474a3">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::addPreRegAlloc</a> and <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a6f3341cb81c2c56307ad3eefc5017c5a">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::addPreSched2</a>.</p>

</div>
</div>

### EnableAtomicTidy {#abae136d266feeb904096250bd5815fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableAtomicTidy("arm-atomic-cfg-tidy", cl::Hidden, cl::desc("Run SimplifyCFG after expanding atomic operations" " to make use of cmpxchg flow-based information"), cl::init(true))</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableGlobalMerge {#a2fad0b7377c229d2a3de9d17a23990ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; EnableGlobalMerge("arm-global-merge", cl::Hidden, cl::desc("Enable the global merge pass"))</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

### false {#acc54b2f9f03c972ad8ae1c851533f1d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arm execution domain ARM Execution Domain false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

### fix {#a86b29362e5d8fbb0d516610e4f988b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arm execution domain fix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

### Fix {#a364a3b69961cc13645dcabbe454f3309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arm execution domain ARM Execution Domain Fix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
