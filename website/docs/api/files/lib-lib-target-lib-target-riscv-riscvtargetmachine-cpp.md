---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVTargetMachine.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-h">RISCVTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvbaseinfo-h">MCTargetDesc/RISCVBaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscv-h">RISCV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmachinefunctioninfo-h">RISCVMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetobjectfile-h">RISCVTargetObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargettransforminfo-h">RISCVTargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/targetinfo/riscvtargetinfo-h">TargetInfo/RISCVTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/irtranslator-h">llvm/CodeGen/GlobalISel/IRTranslator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselect-h">llvm/CodeGen/GlobalISel/InstructionSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizer-h">llvm/CodeGen/GlobalISel/Legalizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/regbankselect-h">llvm/CodeGen/GlobalISel/RegBankSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">llvm/CodeGen/MIRParser/MIParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">llvm/CodeGen/MIRYamlMapping.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/macrofusion-h">llvm/CodeGen/MacroFusion.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">llvm/CodeGen/RegAllocRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetloweringobjectfileimpl-h">llvm/CodeGen/TargetLoweringObjectFileImpl.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/ipo-h">llvm/Transforms/IPO.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopidiomvectorize-h">llvm/Transforms/Vectorize/LoopIdiomVectorize.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvtargetmachine-cpp-">anonymous{RISCVTargetMachine.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/rvvregisterregalloc">RVVRegisterRegAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig">RISCVPassConfig</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b9a09dbbf4b2bacd980a00284a2c143">LLVMInitializeRISCVTarget</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82d112039c4b8a2bf39c9d2c4f51339f">computeDataLayout</a> (const Triple &amp;TT, const TargetOptions &amp;Options)</td>
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

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce6e1e7937f99fa79321a58af27993c">EnableRedundantCopyElimination</a>("riscv-enable-copyelim", cl::desc("Enable the redundant copy elimination pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a182b819dc7dfea9152629d4ce39a9">EnableGlobalMerge</a>("riscv-enable-global-merge", cl::Hidden, cl::desc("Enable the global merge pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af61e3b73d9d43568caa834ee55305ec1">EnableMachineCombiner</a>("riscv-enable-machine-combiner", cl::desc("Enable the machine combiner pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c49454ae268527fd02f0746dd35c409">RVVVectorBitsMaxOpt</a>("riscv-v-vector-bits-max", cl::desc("Assume V extension vector registers are at most this big, " "with zero meaning no maximum size is assumed."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba3fc47199afc874e828812c98b1939d">RVVVectorBitsMinOpt</a>("riscv-v-vector-bits-min", cl::desc("Assume V extension vector registers are at least this big, " "with zero meaning no minimum size is assumed. A value of -1 " "means use Zvl*b extension. This is primarily used to enable " "autovectorization with fixed width vectors."), cl::init(-1), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab219e28b61b68315474ef1e16d4aeb0">EnableRISCVCopyPropagation</a>("riscv-enable-copy-propagation", cl::desc("Enable the copy propagation with RISC-V copy instr"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcedc755a8272f96059255799a2b5e21">EnableRISCVDeadRegisterElimination</a>("riscv-enable-dead-defs", cl::Hidden, cl::desc("Enable the pass that removes dead" " definitons and replaces stores to" " them with stores to x0"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ebe34155cc6d055cbbe75c17110fa49">EnableSinkFold</a>("riscv-enable-sink-fold", cl::desc("Enable sinking and folding of instruction copies"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ed3b8ef93bc4f64465136ae4461106">EnableLoopDataPrefetch</a>("riscv-enable-loop-data-prefetch", cl::Hidden, cl::desc("Enable the loop data prefetch pass"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cbe650dda9aa5650fd2ad40786360a">EnableMISchedLoadStoreClustering</a>("riscv-misched-load-store-clustering", cl::Hidden, cl::desc("Enable load and store clustering in the machine scheduler"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a423c2ea361febbba28d4a403c5c65e1b">EnablePostMISchedLoadStoreClustering</a>("riscv-postmisched-load-store-clustering", cl::Hidden, cl::desc("Enable PostRA load and store clustering in the machine scheduler"), cl::init(true))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b29e0cb8c32c24393f453c7e2c7c4a">EnableVLOptimizer</a>("riscv-enable-vl-optimizer", cl::desc("Enable the RISC-V VL Optimizer pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ed505d7d56ce5cc5cfa5cab9392c87">DisableVectorMaskMutation</a>("riscv-disable-vector-mask-mutation", cl::desc("Disable the vector mask scheduling mutation"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c44ae0ba5086769845735396466ad27">EnableMachinePipeliner</a>("riscv-enable-pipeliner", cl::desc("Enable Machine Pipeliner for RISC-V"), cl::init(false), cl::Hidden)</td>
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

### computeDataLayout() {#a82d112039c4b8a2bf39c9d2c4f51339f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef computeDataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>

</div>
</div>

### LLVMInitializeRISCVTarget() {#a8b9a09dbbf4b2bacd980a00284a2c143}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeRISCVTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3568b368ff108cf4afed7b8ae32ded70">llvm::getTheRISCV32Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab86cdf9a38a9729ea849bcb012fc075d">llvm::getTheRISCV64Target</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa096f48562c0dd3a59ef81dd9126239a">llvm::initializeGlobalISel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf07a4fb8d8926b34d16077ed5c176c5">llvm::initializeKCFIPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab67a4bd596402e9147627ac0b82c7473">llvm::initializeRISCVCodeGenPreparePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7253d5913846bda0508b7b9587cdde00">llvm::initializeRISCVDAGToDAGISelLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e2df9afd4e3787b504f8de56edee434">llvm::initializeRISCVDeadRegisterDefinitionsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1023ae1d1768b0409808f9189af41e59">llvm::initializeRISCVExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad1dd9bb76ae1a4c3808be0af5ee13ef9">llvm::initializeRISCVGatherScatterLoweringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a81bc4c29d65fc0756eb0e664d4f6d14c">llvm::initializeRISCVInsertReadWriteCSRPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a372d99cc1a229ad0e8ef80f12a0cd7cf">llvm::initializeRISCVInsertVSETVLIPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a739bc19589ed017886b079036ce412">llvm::initializeRISCVInsertWriteVXRMPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3fabbd5de1ca536f3c869a0fcc332d2">llvm::initializeRISCVMakeCompressibleOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1383339ebf782d1a94898de582101ad">llvm::initializeRISCVMergeBaseOffsetOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb2fdf53abd85539bfbf2d8efa4aea8b">llvm::initializeRISCVMoveMergePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd7187ed4eabae1c40d7c3c541969633">llvm::initializeRISCVO0PreLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5cff553a4fa92243af54f44a753d99b">llvm::initializeRISCVOptWInstrsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af85f92dc285a3b988b460529fd90cbb9">llvm::initializeRISCVPostLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a677483299bf92363193817f02587460b">llvm::initializeRISCVPostRAExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e54d1e010cb41ea1849cb4cdea441a8">llvm::initializeRISCVPreLegalizerCombinerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aefb9792f73244f499d9abcc4173af42a">llvm::initializeRISCVPreRAExpandPseudoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0eaf5508eee8a34d78411085195c2e80">llvm::initializeRISCVPushPopOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4e1e95549dd096eff5c563b58c12cc4">llvm::initializeRISCVVectorPeepholePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aafa98b1a8c5ff655013e79be481f524d">llvm::initializeRISCVVLOptimizerPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableVectorMaskMutation {#ac8ed505d7d56ce5cc5cfa5cab9392c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableVectorMaskMutation("riscv-disable-vector-mask-mutation", cl::desc("Disable the vector mask scheduling mutation"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a407041e55fa1f623a4ffa56436b5606b">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createMachineScheduler</a>.</p>

</div>
</div>

### EnableGlobalMerge {#a63a182b819dc7dfea9152629d4ce39a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; EnableGlobalMerge("riscv-enable-global-merge", cl::Hidden, cl::desc("Enable the global merge pass"))</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableLoopDataPrefetch {#a52ed3b8ef93bc4f64465136ae4461106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopDataPrefetch("riscv-enable-loop-data-prefetch", cl::Hidden, cl::desc("Enable the loop data prefetch pass"), cl::init(true))</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableMachineCombiner {#af61e3b73d9d43568caa834ee55305ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMachineCombiner("riscv-enable-machine-combiner", cl::desc("Enable the machine combiner pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a79163aeadc46557eb643d6be5dcd37a1">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addMachineSSAOptimization</a>.</p>

</div>
</div>

### EnableMachinePipeliner {#a3c44ae0ba5086769845735396466ad27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMachinePipeliner("riscv-enable-pipeliner", cl::desc("Enable Machine Pipeliner for RISC-V"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableMISchedLoadStoreClustering {#ae6cbe650dda9aa5650fd2ad40786360a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableMISchedLoadStoreClustering("riscv-misched-load-store-clustering", cl::Hidden, cl::desc("Enable load and store clustering in the machine scheduler"), cl::init(true))</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a407041e55fa1f623a4ffa56436b5606b">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createMachineScheduler</a>.</p>

</div>
</div>

### EnablePostMISchedLoadStoreClustering {#a423c2ea361febbba28d4a403c5c65e1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnablePostMISchedLoadStoreClustering("riscv-postmisched-load-store-clustering", cl::Hidden, cl::desc("Enable PostRA load and store clustering in the machine scheduler"), cl::init(true))</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a981486e15f588bdbce922588c8efc899">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createPostMachineScheduler</a>.</p>

</div>
</div>

### EnableRedundantCopyElimination {#a0ce6e1e7937f99fa79321a58af27993c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRedundantCopyElimination("riscv-enable-copyelim", cl::desc("Enable the redundant copy elimination pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableRISCVCopyPropagation {#aab219e28b61b68315474ef1e16d4aeb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRISCVCopyPropagation("riscv-enable-copy-propagation", cl::desc("Enable the copy propagation with RISC-V copy instr"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#acd6595c29823c270fc695147623a1179">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### EnableRISCVDeadRegisterElimination {#adcedc755a8272f96059255799a2b5e21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRISCVDeadRegisterElimination("riscv-enable-dead-defs", cl::Hidden, cl::desc("Enable the pass that removes dead" " definitons and replaces stores to" " them with stores to x0"), cl::init(true))</td>
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



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#ad6a13906a1e82f11750c90da5c8b002c">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addRegAssignAndRewriteFast</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a02591d59a880da83ce4de3f78d24e721">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addRegAssignAndRewriteOptimized</a>.</p>

</div>
</div>

### EnableSinkFold {#a3ebe34155cc6d055cbbe75c17110fa49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSinkFold("riscv-enable-sink-fold", cl::desc("Enable sinking and folding of instruction copies"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableVLOptimizer {#a45b29e0cb8c32c24393f453c7e2c7c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableVLOptimizer("riscv-enable-vl-optimizer", cl::desc("Enable the RISC-V VL Optimizer pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#acdb50f4d9f449524cc16b192b03979e1">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### RVVVectorBitsMaxOpt {#a5c49454ae268527fd02f0746dd35c409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; RVVVectorBitsMaxOpt("riscv-v-vector-bits-max", cl::desc("Assume V extension vector registers are at most this big, " "with zero meaning no maximum size is assumed."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

### RVVVectorBitsMinOpt {#aba3fc47199afc874e828812c98b1939d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; int &gt; RVVVectorBitsMinOpt("riscv-v-vector-bits-min", cl::desc("Assume V extension vector registers are at least this big, " "with zero meaning no minimum size is assumed. A value of -1 " "means use Zvl*b extension. This is primarily used to enable " "autovectorization with fixed width vectors."), cl::init(-1), cl::Hidden)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvtargetmachine/#a3303f4528ff6f8538d036d62e3d25751">llvm::RISCVTargetMachine::getSubtargetImpl</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
