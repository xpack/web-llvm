---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `WebAssemblyTargetMachine.cpp` File Reference

<p>This file defines the WebAssembly-specific subclass of <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-h">WebAssemblyTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">MCTargetDesc/WebAssemblyMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/targetinfo/webassemblytargetinfo-h">TargetInfo/WebAssemblyTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassembly-h">WebAssembly.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-h">WebAssemblyISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymachinefunctioninfo-h">WebAssemblyMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetobjectfile-h">WebAssemblyTargetObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargettransforminfo-h">WebAssemblyTargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyutilities-h">WebAssemblyUtilities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/mirparser/miparser-h">llvm/CodeGen/MIRParser/MIParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/regallocregistry-h">llvm/CodeGen/RegAllocRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcasminfo-h">llvm/MC/MCAsmInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetoptions-h">llvm/Target/TargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/loweratomicpass-h">llvm/Transforms/Scalar/LowerAtomicPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/utils-h">llvm/Transforms/Utils.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-webassemblytargetmachine-cpp-">anonymous{WebAssemblyTargetMachine.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/coalescefeaturesandstripatomics">CoalesceFeaturesAndStripAtomics</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig">WebAssemblyPassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/webassembly">WebAssembly</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5193d47b6ee96653d85049ae1ab002e9">LLVMInitializeWebAssemblyTarget</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225188450747cb01da5afaea151ff9db">getEffectiveRelocModel</a> (std::optional&lt; Reloc::Model &gt; RM, const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563cec1174cd4374050fc2c3007b26a9">basicCheckForEHAndSjLj</a> (TargetMachine *TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16f99939d8bae4daf4d01bda3e30382">WasmDisableExplicitLocals</a>("wasm-disable-explicit-locals", cl::Hidden, cl::desc("WebAssembly: output implicit locals in" " instruction output for test purposes only."), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9ca35b245dba6c3ae892b4bb4d79ea4">WasmDisableFixIrreducibleControlFlowPass</a>("wasm-disable-fix-irreducible-control-flow-pass", cl::Hidden, cl::desc("webassembly: disables the fix " " irreducible control flow optimization pass"), cl::init(false))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"wasm"</td>
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

<p>This file defines the WebAssembly-specific subclass of <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>.</p>

<div class="doxySectionDef">

## Functions

### basicCheckForEHAndSjLj() {#a563cec1174cd4374050fc2c3007b26a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void basicCheckForEHAndSjLj (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84af93da81fd23e2eeaf8de29b04bb2399f">llvm::Wasm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig/#aeb170544eb9997045ad3d9084cccccc0">anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::addIRPasses</a>.</p>

</div>
</div>

### getEffectiveRelocModel() {#a225188450747cb01da5afaea151ff9db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model getEffectiveRelocModel (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>

</div>
</div>

### LLVMInitializeWebAssemblyTarget() {#a5193d47b6ee96653d85049ae1ab002e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeWebAssemblyTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7eaefe3d08d9d3f62944e9074df84ba6">llvm::getTheWebAssemblyTarget32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaa7fdcba17ac3f1f7aebc5edfe48c13a">llvm::getTheWebAssemblyTarget64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4bbf1036f6aca39416fab45f2084c81">llvm::initializeFixFunctionBitcastsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7950583043c424c49e7b5a97bee319d2">llvm::initializeLowerGlobalDtorsLegacyPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a015eb75232a3da03c5a2680a6339d986">llvm::initializeOptimizeReturnedPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2fe4e6215508febed5776106a5331a9e">llvm::initializeWebAssemblyAddMissingPrototypesPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af93dd8c36a1ffb34c1042819a71f9d5a">llvm::initializeWebAssemblyArgumentMovePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae0dc9c7fa2c3e7c7680c8143ec7cf0ae">llvm::initializeWebAssemblyCFGSortPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aefbb98e8ecfe7ac6dd40c5ab36ec2609">llvm::initializeWebAssemblyCFGStackifyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a45527dc95857578fcf1f7ec960700eb9">llvm::initializeWebAssemblyDAGToDAGISelLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1454441604dc893e72f95494c51bf1f">llvm::initializeWebAssemblyDebugFixupPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3f450b1f8c41aadd499a4d94952d70">llvm::initializeWebAssemblyExceptionInfoPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab27dfdb3309c48d5943b339fed0b7e27">llvm::initializeWebAssemblyExplicitLocalsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae490ea3e56f9a9a7ee2c623295f2de93">llvm::initializeWebAssemblyFixBrTableDefaultsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846594b95f81a54e9db912dce2552fd2">llvm::initializeWebAssemblyFixIrreducibleControlFlowPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c10081f972d305e7c15620119c377c0">llvm::initializeWebAssemblyLateEHPreparePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05775b3c0e84fbe056684e28747b8e44">llvm::initializeWebAssemblyLowerBrUnlessPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb3911cac32d8629a434068e8d16733">llvm::initializeWebAssemblyLowerEmscriptenEHSjLjPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a450ae16b83753088c7b369e67bada03a">llvm::initializeWebAssemblyLowerRefTypesIntPtrConvPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2178295feee430d3f86953224706e09">llvm::initializeWebAssemblyMCLowerPrePassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1cc778918ea20a2daf42371b2b4f1d9">llvm::initializeWebAssemblyMemIntrinsicResultsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f8b47ac93d917e30c0690bee9425987">llvm::initializeWebAssemblyNullifyDebugValueListsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a981585f13eb8a8cd4a2cd8807a434804">llvm::initializeWebAssemblyOptimizeLiveIntervalsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4c61f4be737c7ea117ee0c9371f0f45">llvm::initializeWebAssemblyPeepholePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad55a4c24509199a39f45fab37256dcac">llvm::initializeWebAssemblyRefTypeMem2LocalPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6b80327d26479b479a0536fee4a7f6">llvm::initializeWebAssemblyRegColoringPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43066d1437e59118e1bc255e972e3179">llvm::initializeWebAssemblyRegNumberingPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8613fe7739c0449d0f541b7a3475c2f5">llvm::initializeWebAssemblyRegStackifyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afed9c1f4c108bac348ddd9be3858d78f">llvm::initializeWebAssemblyReplacePhysRegsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af0512b1c7b8e688e606e6d1224047226">llvm::initializeWebAssemblySetP2AlignOperandsPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### WasmDisableExplicitLocals {#ac16f99939d8bae4daf4d01bda3e30382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; WasmDisableExplicitLocals("wasm-disable-explicit-locals", cl::Hidden, cl::desc("WebAssembly: output implicit locals in" " instruction output for test purposes only."), cl::init(false))</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig/#ab4beb7113336e36d1a81ae2ca8ca6d52">anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### WasmDisableFixIrreducibleControlFlowPass {#af9ca35b245dba6c3ae892b4bb4d79ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; WasmDisableFixIrreducibleControlFlowPass("wasm-disable-fix-irreducible-control-flow-pass", cl::Hidden, cl::desc("webassembly: disables the fix " " irreducible control flow optimization pass"), cl::init(false))</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblytargetmachine-cpp-/webassemblypassconfig/#ab4beb7113336e36d1a81ae2ca8ca6d52">anonymous{WebAssemblyTargetMachine.cpp}::WebAssemblyPassConfig::addPreEmitPass</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"wasm"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp">WebAssemblyTargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
