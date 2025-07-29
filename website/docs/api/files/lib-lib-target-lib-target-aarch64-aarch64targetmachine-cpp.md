---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AArch64TargetMachine.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-h">AArch64TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-h">AArch64MachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinescheduler-h">AArch64MachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64macrofusion-h">AArch64MacroFusion.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-h">AArch64TargetObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-h">AArch64TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-h">MCTargetDesc/AArch64MCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/targetinfo/aarch64targetinfo-h">TargetInfo/AArch64TargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/valuetracking-h">llvm/Analysis/ValueTracking.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/cseconfigbase-h">llvm/CodeGen/CSEConfigBase.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/irtranslator-h">llvm/CodeGen/GlobalISel/IRTranslator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselect-h">llvm/CodeGen/GlobalISel/InstructionSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizer-h">llvm/CodeGen/GlobalISel/Legalizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/loadstoreopt-h">llvm/CodeGen/GlobalISel/LoadStoreOpt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/localizer-h">llvm/CodeGen/GlobalISel/Localizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">llvm/CodeGen/MIRParser/MIParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">llvm/Support/CodeGen.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetloweringobjectfile-h">llvm/Target/TargetLoweringObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/cfguard-h">llvm/Transforms/CFGuard.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/lowerifunc-h">llvm/Transforms/Utils/LowerIFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopidiomvectorize-h">llvm/Transforms/Vectorize/LoopIdiomVectorize.h</a>"
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64targetmachine-cpp-">anonymous{AArch64TargetMachine.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig">AArch64PassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/aarch64">AArch64</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29f792516a692b403e4f66d9815002f">LLVMInitializeAArch64Target</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a003a58caf135efbf7273c5ed84e700d7">computeDataLayout</a> (const Triple &amp;TT, const MCTargetOptions &amp;Options, bool LittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4afdd1c52c4d1ae5b080edbc7aac3db3">computeDefaultCPU</a> (const Triple &amp;TT, StringRef CPU)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5732ecb60ad8bdaacba9c6de50764c">getEffectiveAArch64CodeModel</a> (const Triple &amp;TT, std::optional&lt; CodeModel::Model &gt; CM, bool JIT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc92736eaec941441cda197e6ddb5fb1">EnableCCMP</a>("aarch64-enable-ccmp", cl::desc("Enable the CCMP formation pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e23687830431b9783ae2a8ba5c67322">EnableCondBrTuning</a>("aarch64-enable-cond-br-tune", cl::desc("Enable the conditional branch tuning pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1785b93df5b7ad6aa41c89303c038918">EnableAArch64CopyPropagation</a>("aarch64-enable-copy-propagation", cl::desc("Enable the copy propagation with AArch64 copy instr"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b725f539bbd34f207d899bb5430785">EnableMCR</a>("aarch64-enable-mcr", cl::desc("Enable the machine combiner pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71dbfc9c44945a2693da355515d834d2">EnableStPairSuppress</a>("aarch64-enable-stp-suppress", cl::desc("Suppress STP for AArch64"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9bf0b1ed5b4680b9a2ed8ec1b4d8c7a">EnableAdvSIMDScalar</a>("aarch64-enable-simd-scalar", cl::desc("Enable use of AdvSIMD scalar integer instructions"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e1ae0d5f3a12d751e70b178cd6ad69a">EnablePromoteConstant</a>("aarch64-enable-promote-const", cl::desc("Enable the promote constant pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2f133fbd8a49b8bc1553955955cf23">EnableCollectLOH</a>("aarch64-enable-collect-loh", cl::desc("Enable the pass that emits the linker optimization hints (LOH)"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310081f3bb70c1ad1fe5dc36b69f7e36">EnableDeadRegisterElimination</a>("aarch64-enable-dead-defs", cl::Hidden, cl::desc("Enable the pass that removes dead" " definitions and replaces stores to" " them with stores to the zero" " register"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab116eea21c829ed214f066676ba08711">EnableRedundantCopyElimination</a>("aarch64-enable-copyelim", cl::desc("Enable the redundant copy elimination pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a442e4d0e3c6d6fc78ce6995d35fcda6e">EnableLoadStoreOpt</a>("aarch64-enable-ldst-opt", cl::desc("Enable the load/store pair" " optimization pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74b3e25dc3e12d9f164d1200fcf9495">EnableAtomicTidy</a>("aarch64-enable-atomic-cfg-tidy", cl::Hidden, cl::desc("Run SimplifyCFG after expanding atomic operations" " to make use of cmpxchg flow-based information"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad406e3834655b047b66b1ff9cb4b43c8">EnableEarlyIfConversion</a>("aarch64-enable-early-ifcvt", cl::Hidden, cl::desc("Run early if-conversion"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98cb91602aae6c876e7fa15a2550ae4b">EnableCondOpt</a>("aarch64-enable-condopt", cl::desc("Enable the condition optimizer pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e0a4ad7a6d508dea693b02deacd874">EnableGEPOpt</a>("aarch64-enable-gep-opt", cl::Hidden, cl::desc("Enable optimizations on complex GEPs"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402d70cf47b586196e979c940a3bda75">EnableSelectOpt</a>("aarch64-select-opt", cl::Hidden, cl::desc("Enable select to branch optimizations"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e189295e53ef7252e5955f320334a2">BranchRelaxation</a>("aarch64-enable-branch-relax", cl::Hidden, cl::init(true), cl::desc("Relax out of range conditional branches"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f34f6c3dc48f1f758719cfc44b8a71">EnableCompressJumpTables</a>("aarch64-enable-compress-jump-tables", cl::Hidden, cl::init(true), cl::desc("Use smallest entry possible for jump tables"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60720411b8706ce68088f99b82971564">EnableGlobalMerge</a>("aarch64-enable-global-merge", cl::Hidden, cl::desc("Enable the global merge pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c62565f35006824b9f25fe3ae028cc">EnableLoopDataPrefetch</a>("aarch64-enable-loop-data-prefetch", cl::Hidden, cl::desc("Enable the loop data prefetch pass"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe42b4ea2f464b73322e82fb8ede59fb">EnableGlobalISelAtO</a>("aarch64-enable-global-isel-at-O", cl::Hidden, cl::desc("Enable GlobalISel at or below an opt level (-1 to disable)"), cl::init(0))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e313458d44866783dc37c637ad4136b">EnableSVEIntrinsicOpts</a>("aarch64-enable-sve-intrinsic-opts", cl::Hidden, cl::desc("Enable SVE intrinsic opts"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e5a0bbb4a5167b2b8aa561bce8da32">EnableSMEPeepholeOpt</a>("enable-aarch64-sme-peephole-opt", cl::init(true), cl::Hidden, cl::desc("Perform SME peephole optimization"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9c215835e347a83d9b24375b69fa13">EnableFalkorHWPFFix</a>("aarch64-enable-falkor-hwpf-fix", cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05e181915ab2df5b003c5a3eeb15219f">EnableBranchTargets</a>("aarch64-enable-branch-targets", cl::Hidden, cl::desc("Enable the AArch64 branch target pass"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae870969f61cc5827f2a334e224cb7e6c">SVEVectorBitsMaxOpt</a>("aarch64-sve-vector-bits-max", cl::desc("Assume SVE vector registers are at most this big, " "with zero meaning no maximum size is assumed."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51941b603cdd7cca646ac2e6faad8fa2">SVEVectorBitsMinOpt</a>("aarch64-sve-vector-bits-min", cl::desc("Assume SVE vector registers are at least this big, " "with zero meaning no minimum size is assumed."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa777eedb3b3968b2aafacd12a87ae171">ForceStreaming</a>("force-streaming", cl::desc("Force the use of streaming code for all functions"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3591861868efa944d79290e244f1209">ForceStreamingCompatible</a>("force-streaming-compatible", cl::desc("Force the use of streaming-compatible code for all functions"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f3cef1ba9c012e32a1630255b02e52">EnableHomogeneousPrologEpilog</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadafc8d88628f006a01a7b5227c49c81">EnableGISelLoadStoreOptPreLegal</a>("aarch64-enable-gisel-ldst-prelegal", cl::desc("Enable GlobalISel's pre-legalizer load/store optimization pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f483f26103bcd9249e0c8319217f46">EnableGISelLoadStoreOptPostLegal</a>("aarch64-enable-gisel-ldst-postlegal", cl::desc("Enable GlobalISel's post-legalizer load/store optimization pass"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e23d3db2edb9b94dd6df4f78d8a4166">EnableSinkFold</a>("aarch64-enable-sink-fold", cl::desc("Enable sinking and folding of instruction copies"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf236a077b71d539a7e12cbf9df34313">EnableMachinePipeliner</a>("aarch64-enable-pipeliner", cl::desc("Enable Machine Pipeliner for AArch64"), cl::init(false), cl::Hidden)</td>
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

### computeDataLayout() {#a003a58caf135efbf7273c5ed84e700d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string computeDataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options, bool LittleEndian)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af26b2aa05e5a49b91b981143e0e49a34">llvm::Triple::aarch64_32</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a0a05a130bb4b1c97244ff98d64e0de5d">llvm::Triple::GNUILP32</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/bpftargetmachine/#ab8863575f43949311ae24b598155dc09">llvm::BPFTargetMachine::BPFTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/cskytargetmachine/#a633e7df96afce72a4e730ecb6e95e6b2">llvm::CSKYTargetMachine::CSKYTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetmachine/#ad4c676bf9a496db85baa599666ac50b8">llvm::LanaiTargetMachine::LanaiTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetmachine/#a04a47a45b26a93d11e3cc1b92dfe1281">llvm::LoongArchTargetMachine::LoongArchTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine/#ab461a12892a3c384f080db036b2234a1">llvm::M68kTargetMachine::M68kTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetmachine/#a204cc56ded2a0d2743a71edbb2329524">llvm::MSP430TargetMachine::MSP430TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetmachine/#a78a93424a800f37fc3a2162c836c9eee">llvm::NVPTXTargetMachine::NVPTXTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a263886b11be7dae786aa918f70e909b8">llvm::RISCVTargetMachine::RISCVTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetmachine/#a6a12b8b4d104e9370700c6441df0b7aa">llvm::SparcTargetMachine::SparcTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvtargetmachine/#a5f24bce1cade82dd36f855453d0f4781">llvm::SPIRVTargetMachine::SPIRVTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ab6e0c470f6d0cc116c75811bdf41bb">llvm::SystemZTargetMachine::SystemZTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetmachine/#a3ac52cbfedf6698e050636a061cfff0c">llvm::VETargetMachine::VETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/xtensatargetmachine/#a95a957a4ac339769f3090d57a1bb6815">llvm::XtensaTargetMachine::XtensaTargetMachine</a>.</p>

</div>
</div>

### computeDefaultCPU() {#a4afdd1c52c4d1ae5b080edbc7aac3db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef computeDefaultCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU)</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>.</p>

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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetmachine/#a5d81421a7c6e65b440e6a2deff9beaa6">llvm::AMDGPUTargetMachine::AMDGPUTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armbasetargetmachine/#af24525644c0d188c873f506b53891787">llvm::ARMBaseTargetMachine::ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetmachine/#a72542aebd8b9fca8e738edac73af1810">llvm::MipsTargetMachine::MipsTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine/#a9329650dea81789565d4d4e7019c81eb">llvm::PPCTargetMachine::PPCTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetmachine/#a3ab6e0c470f6d0cc116c75811bdf41bb">llvm::SystemZTargetMachine::SystemZTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetmachine/#a3ac52cbfedf6698e050636a061cfff0c">llvm::VETargetMachine::VETargetMachine</a> and <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine/#aee4969629bf56864f2d3058bcba4506f">llvm::X86TargetMachine::X86TargetMachine</a>.</p>

</div>
</div>

### getEffectiveAArch64CodeModel() {#a8e5732ecb60ad8bdaacba9c6de50764c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeModel::Model getEffectiveAArch64CodeModel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, bool JIT)</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>.</p>

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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a455bffdcf9dfc03e4b8f11c6085d0f3e">llvm::Reloc::DynamicNoPIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">llvm::Reloc::PIC_</a> and <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>

</div>
</div>

### LLVMInitializeAArch64Target() {#ad29f792516a692b403e4f66d9815002f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeAArch64Target ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6801bd0c4f489c415aa4dd112f689431">llvm::getTheAArch64_32Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35741a6418a8623f73066fb4cfe60f6e">llvm::getTheAArch64beTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5504cff079de2ebf921f62c1734de177">llvm::getTheAArch64leTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9822de3617fc8c79df9cefed09ecd5dc">llvm::getTheARM64_32Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3383917acb3327d70b33774b69e9d23">llvm::getTheARM64Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4a5275d3f956a9f220d92830dc4d314">llvm::initializeAArch64A53Fix835769Pass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a09c5ecd09d85200e938567c97c20ffa5">llvm::initializeAArch64A57FPLoadBalancingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2069e08888cfcfe2008876b615609bfd">llvm::initializeAArch64AdvSIMDScalarPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1c7640f9e0cd408c4f83d42d8276829">llvm::initializeAArch64BranchTargetsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad573933728f7ce6338d555abaf95eafa">llvm::initializeAArch64CollectLOHPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a838f3fdbcce2b62882e64487b7b2490b">llvm::initializeAArch64CompressJumpTablesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade08d45fe60a1c623b06feb812f49972">llvm::initializeAArch64ConditionalComparesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adca4479ea6b3bada617933e6a133b434">llvm::initializeAArch64ConditionOptimizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6beb0d8fd5b2aee6075e8efbba11b0e">llvm::initializeAArch64DAGToDAGISelLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70febd1bd6ec629445aada840f28cb5a">llvm::initializeAArch64DeadRegisterDefinitionsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f6db2dad0088524936006a52514cf73">llvm::initializeAArch64ExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac984e10b62f9eb21b5ffdd07c1a12fb2">llvm::initializeAArch64LoadStoreOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b0e25a664f8cec0729ead6cb2e5f9c2">llvm::initializeAArch64LowerHomogeneousPrologEpilogPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab110338a1e774aebf1ecc446020e5b3">llvm::initializeAArch64MIPeepholeOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb2731bda0de20e7c2becd285aa4a30f">llvm::initializeAArch64O0PreLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee5c18aa78295f4d143428e84b366cb0">llvm::initializeAArch64PointerAuthPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21373a7e533dc8c0a4bcb10ca319235b">llvm::initializeAArch64PostCoalescerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1d67c2ec215f362f90657a2ef809c449">llvm::initializeAArch64PostLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a199d6087e8d7814677e5483a01975a60">llvm::initializeAArch64PostLegalizerLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1c901902fbe78ea8c4f7a00baf09b5b">llvm::initializeAArch64PostSelectOptimizePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a954fe84f83faacfa1cfe2c4482e1c4e6">llvm::initializeAArch64PreLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a31f7820c2baf31ef6792320e105af10d">llvm::initializeAArch64PromoteConstantPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0f3d79982f11f47caf397b9ece79eb4">llvm::initializeAArch64RedundantCopyEliminationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ace01ea1de28709257e8236ec413931f1">llvm::initializeAArch64SIMDInstrOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a843419243b2115dee32153a1e634ed07">llvm::initializeAArch64SLSHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19868a7ed3edb88d1438287f742884b8">llvm::initializeAArch64SpeculationHardeningPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71f2bad8e219fc019bdc1d93c5687266">llvm::initializeAArch64StackTaggingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a905f96c85788f5247e25e00a899317c7">llvm::initializeAArch64StackTaggingPreRAPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9af91adf64cebcd227091b727afd10e9">llvm::initializeAArch64StorePairSuppressPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab57f8d23fa01364894a0d0ddb72d46e4">llvm::initializeFalkorHWPFFixPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f1567882f5e73c437f9b14d947f83f0">llvm::initializeFalkorMarkStridedAccessesLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa096f48562c0dd3a59ef81dd9126239a">llvm::initializeGlobalISel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf07a4fb8d8926b34d16077ed5c176c5">llvm::initializeKCFIPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05b594b58a0bc7a400c45b32ab11d1bf">llvm::initializeLDTLSCleanupPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4faf2bd70fff1d4fd255614b603da902">llvm::initializeSMEABIPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dfd460c7ef71d907fab9dc84e3a878e">llvm::initializeSMEPeepholeOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec10b60647bd1d0990cbdee4eb5c591e">llvm::initializeSVEIntrinsicOptsPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BranchRelaxation {#a17e189295e53ef7252e5955f320334a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; BranchRelaxation("aarch64-enable-branch-relax", cl::Hidden, cl::init(true), cl::desc("Relax out of range conditional branches"))</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ad0d91382d623d77443845dde96202b91">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPostBBSections</a> and <a href="/web-llvm/docs/api/classes/anonymous-sparctargetmachine-cpp-/sparcpassconfig/#a1c0b9525cb7c73b2925a2c4fb43b3788">anonymous{SparcTargetMachine.cpp}::SparcPassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### EnableAArch64CopyPropagation {#a1785b93df5b7ad6aa41c89303c038918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableAArch64CopyPropagation("aarch64-enable-copy-propagation", cl::desc("Enable the copy propagation with AArch64 copy instr"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a133b56fc6ec387a6ddad9bd9f23eb4d1">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### EnableAdvSIMDScalar {#ab9bf0b1ed5b4680b9a2ed8ec1b4d8c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableAdvSIMDScalar("aarch64-enable-simd-scalar", cl::desc("Enable use of AdvSIMD scalar integer instructions"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ac305cefffb34482da2d19c54e347caa6">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableAtomicTidy {#ab74b3e25dc3e12d9f164d1200fcf9495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableAtomicTidy("aarch64-enable-atomic-cfg-tidy", cl::Hidden, cl::desc("Run SimplifyCFG after expanding atomic operations" " to make use of cmpxchg flow-based information"), cl::init(true))</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a893766a6f5979c280a6d937a4d51bb75">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armpassconfig/#a515443562ac3481d446c87317b603861">anonymous{ARMTargetMachine.cpp}::ARMPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableBranchTargets {#a05e181915ab2df5b003c5a3eeb15219f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableBranchTargets("aarch64-enable-branch-targets", cl::Hidden, cl::desc("Enable the AArch64 branch target pass"), cl::init(true))</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ad0d91382d623d77443845dde96202b91">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPostBBSections</a>.</p>

</div>
</div>

### EnableCCMP {#afc92736eaec941441cda197e6ddb5fb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCCMP("aarch64-enable-ccmp", cl::desc("Enable the CCMP formation pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ae93142e0240a03a005fa2f52ff28e706">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addILPOpts</a>.</p>

</div>
</div>

### EnableCollectLOH {#aad2f133fbd8a49b8bc1553955955cf23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCollectLOH("aarch64-enable-collect-loh", cl::desc("Enable the pass that emits the linker optimization hints (LOH)"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a133b56fc6ec387a6ddad9bd9f23eb4d1">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### EnableCompressJumpTables {#af4f34f6c3dc48f1f758719cfc44b8a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCompressJumpTables("aarch64-enable-compress-jump-tables", cl::Hidden, cl::init(true), cl::desc("Use smallest entry possible for jump tables"))</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ad0d91382d623d77443845dde96202b91">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPostBBSections</a>.</p>

</div>
</div>

### EnableCondBrTuning {#a1e23687830431b9783ae2a8ba5c67322}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCondBrTuning("aarch64-enable-cond-br-tune", cl::desc("Enable the conditional branch tuning pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ae93142e0240a03a005fa2f52ff28e706">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addILPOpts</a>.</p>

</div>
</div>

### EnableCondOpt {#a98cb91602aae6c876e7fa15a2550ae4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCondOpt("aarch64-enable-condopt", cl::desc("Enable the condition optimizer pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ae93142e0240a03a005fa2f52ff28e706">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addILPOpts</a>.</p>

</div>
</div>

### EnableDeadRegisterElimination {#a310081f3bb70c1ad1fe5dc36b69f7e36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableDeadRegisterElimination("aarch64-enable-dead-defs", cl::Hidden, cl::desc("Enable the pass that removes dead" " definitions and replaces stores to" " them with stores to the zero" " register"), cl::init(true))</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ac305cefffb34482da2d19c54e347caa6">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableEarlyIfConversion {#ad406e3834655b047b66b1ff9cb4b43c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableEarlyIfConversion("aarch64-enable-early-ifcvt", cl::Hidden, cl::desc("Run early if-conversion"), cl::init(true))</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ae93142e0240a03a005fa2f52ff28e706">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addILPOpts</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a57d63513d35cc11cffba6cc0e1aedd6c">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::addILPOpts</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpucodegenpassbuilder/#ab8c3d4837ac7e391cd0243717b32b3b1">llvm::AMDGPUCodeGenPassBuilder::addILPOpts</a>.</p>

</div>
</div>

### EnableFalkorHWPFFix {#adf9c215835e347a83d9b24375b69fa13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableFalkorHWPFFix("aarch64-enable-falkor-hwpf-fix", cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a893766a6f5979c280a6d937a4d51bb75">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a1e02ef6d484e1b3d856b0ad1416ff810">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreSched2</a>.</p>

</div>
</div>

### EnableGEPOpt {#a36e0a4ad7a6d508dea693b02deacd874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGEPOpt("aarch64-enable-gep-opt", cl::Hidden, cl::desc("Enable optimizations on complex GEPs"), cl::init(false))</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a893766a6f5979c280a6d937a4d51bb75">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/classes/anonymous-ppctargetmachine-cpp-/ppcpassconfig/#a8c16916d71dc36409cdc255e86eb769d">anonymous{PPCTargetMachine.cpp}::PPCPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableGISelLoadStoreOptPostLegal {#a47f483f26103bcd9249e0c8319217f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGISelLoadStoreOptPostLegal("aarch64-enable-gisel-ldst-postlegal", cl::desc("Enable GlobalISel's post-legalizer load/store optimization pass"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a71cee5c16c8e10d2eb03f6bcbeaff9a9">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreRegBankSelect</a>.</p>

</div>
</div>

### EnableGISelLoadStoreOptPreLegal {#aadafc8d88628f006a01a7b5227c49c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGISelLoadStoreOptPreLegal("aarch64-enable-gisel-ldst-prelegal", cl::desc("Enable GlobalISel's pre-legalizer load/store optimization pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a66645743ba2e3e7179aa52fba667927f">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreLegalizeMachineIR</a>.</p>

</div>
</div>

### EnableGlobalISelAtO {#abe42b4ea2f464b73322e82fb8ede59fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; EnableGlobalISelAtO("aarch64-enable-global-isel-at-O", cl::Hidden, cl::desc("Enable GlobalISel at or below an opt level (-1 to disable)"), cl::init(0))</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#ad68ba4232115bf14e4b34e3f02ec40bc">llvm::AArch64TargetMachine::AArch64TargetMachine</a>.</p>

</div>
</div>

### EnableGlobalMerge {#a60720411b8706ce68088f99b82971564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; EnableGlobalMerge("aarch64-enable-global-merge", cl::Hidden, cl::desc("Enable the global merge pass"))</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>

</div>
</div>

### EnableHomogeneousPrologEpilog {#a46f3cef1ba9c012e32a1630255b02e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; EnableHomogeneousPrologEpilog</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>

</div>
</div>

### EnableLoadStoreOpt {#a442e4d0e3c6d6fc78ce6995d35fcda6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoadStoreOpt("aarch64-enable-ldst-opt", cl::desc("Enable the load/store pair" " optimization pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a133b56fc6ec387a6ddad9bd9f23eb4d1">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreEmitPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a1e02ef6d484e1b3d856b0ad1416ff810">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreSched2</a>.</p>

</div>
</div>

### EnableLoopDataPrefetch {#ac4c62565f35006824b9f25fe3ae028cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopDataPrefetch("aarch64-enable-loop-data-prefetch", cl::Hidden, cl::desc("Enable the loop data prefetch pass"), cl::init(true))</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a893766a6f5979c280a6d937a4d51bb75">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addIRPasses</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchtargetmachine-cpp-/loongarchpassconfig/#af53c206ae716686677ba1ef1a3f96c96">anonymous{LoongArchTargetMachine.cpp}::LoongArchPassConfig::addIRPasses</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a84e61fde0e7b339c7d80bffc620cae9e">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableMachinePipeliner {#adf236a077b71d539a7e12cbf9df34313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMachinePipeliner("aarch64-enable-pipeliner", cl::desc("Enable Machine Pipeliner for AArch64"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ac305cefffb34482da2d19c54e347caa6">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreRegAlloc</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#acdb50f4d9f449524cc16b192b03979e1">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addPreRegAlloc</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a0d6327aed5635c20926eb30e65db5e83">llvm::PPCSubtarget::enableMachinePipeliner</a>.</p>

</div>
</div>

### EnableMCR {#a54b725f539bbd34f207d899bb5430785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMCR("aarch64-enable-mcr", cl::desc("Enable the machine combiner pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ae93142e0240a03a005fa2f52ff28e706">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addILPOpts</a>.</p>

</div>
</div>

### EnablePromoteConstant {#a1e1ae0d5f3a12d751e70b178cd6ad69a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePromoteConstant("aarch64-enable-promote-const", cl::desc("Enable the promote constant pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a40314d5e1634192397b4d4e4d78b73c0">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPreISel</a>.</p>

</div>
</div>

### EnableRedundantCopyElimination {#ab116eea21c829ed214f066676ba08711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRedundantCopyElimination("aarch64-enable-copyelim", cl::desc("Enable the redundant copy elimination pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#af12ca69c1858fb1e0df616b9243ac96c">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addPostRegAlloc</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#acd7a622a58a666a25265fae614784ca8">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addPostRegAlloc</a>.</p>

</div>
</div>

### EnableSelectOpt {#a402d70cf47b586196e979c940a3bda75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSelectOpt("aarch64-select-opt", cl::Hidden, cl::desc("Enable select to branch optimizations"), cl::init(true))</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a893766a6f5979c280a6d937a4d51bb75">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableSinkFold {#a2e23d3db2edb9b94dd6df4f78d8a4166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSinkFold("aarch64-enable-sink-fold", cl::desc("Enable sinking and folding of instruction copies"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ab28524895802517d8f53e5fe7ce3bdf3">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::AArch64PassConfig</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#aff91c4562be0d3d5fbf198128208b7b3">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::RISCVPassConfig</a>.</p>

</div>
</div>

### EnableSMEPeepholeOpt {#ac9e5a0bbb4a5167b2b8aa561bce8da32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSMEPeepholeOpt("enable-aarch64-sme-peephole-opt", cl::init(true), cl::Hidden, cl::desc("Perform SME peephole optimization"))</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a30443d291730c6d57a500f7c7fdaa92f">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addMachineSSAOptimization</a>.</p>

</div>
</div>

### EnableStPairSuppress {#a71dbfc9c44945a2693da355515d834d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableStPairSuppress("aarch64-enable-stp-suppress", cl::desc("Suppress STP for AArch64"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#ae93142e0240a03a005fa2f52ff28e706">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addILPOpts</a>.</p>

</div>
</div>

### EnableSVEIntrinsicOpts {#a0e313458d44866783dc37c637ad4136b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSVEIntrinsicOpts("aarch64-enable-sve-intrinsic-opts", cl::Hidden, cl::desc("Enable SVE intrinsic opts"), cl::init(true))</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64targetmachine-cpp-/aarch64passconfig/#a893766a6f5979c280a6d937a4d51bb75">anonymous{AArch64TargetMachine.cpp}::AArch64PassConfig::addIRPasses</a>.</p>

</div>
</div>

### ForceStreaming {#aa777eedb3b3968b2aafacd12a87ae171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceStreaming("force-streaming", cl::desc("Force the use of streaming code for all functions"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

### ForceStreamingCompatible {#af3591861868efa944d79290e244f1209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ForceStreamingCompatible("force-streaming-compatible", cl::desc("Force the use of streaming-compatible code for all functions"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

### SVEVectorBitsMaxOpt {#ae870969f61cc5827f2a334e224cb7e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SVEVectorBitsMaxOpt("aarch64-sve-vector-bits-max", cl::desc("Assume SVE vector registers are at most this big, " "with zero meaning no maximum size is assumed."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

### SVEVectorBitsMinOpt {#a51941b603cdd7cca646ac2e6faad8fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; SVEVectorBitsMinOpt("aarch64-sve-vector-bits-min", cl::desc("Assume SVE vector registers are at least this big, " "with zero meaning no minimum size is assumed."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp">AArch64TargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetmachine/#a9e5bf74a8a222c830855fd1adb3ae07e">llvm::AArch64TargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
