---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `HexagonTargetMachine.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-h">HexagonTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagon-h">Hexagon.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonisellowering-h">HexagonISelLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloopidiomrecognition-h">HexagonLoopIdiomRecognition.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinefunctioninfo-h">HexagonMachineFunctionInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonmachinescheduler-h">HexagonMachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetobjectfile-h">HexagonTargetObjectFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargettransforminfo-h">HexagonTargetTransformInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonvectorloopcarriedreuse-h">HexagonVectorLoopCarriedReuse.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/targetinfo/hexagontargetinfo-h">TargetInfo/HexagonTargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/vliwmachinescheduler-h">llvm/CodeGen/VLIWMachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/passes/passbuilder-h">llvm/Passes/PassBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/scalar-h">llvm/Transforms/Scalar.h</a>"
#include &lt;optional&gt;
#include "llvm/Passes/TargetPassRegistry.inc"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-hexagontargetmachine-cpp-">anonymous{HexagonTargetMachine.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig">HexagonPassConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/hexagon">Hexagon</a> Code Generator <a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> Configuration Options. <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab77d912a7ea86c5c77bc6eacb9adca6">createVLIWMachineSched</a> (MachineSchedContext *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a906e08cf722c544eeff0ae4295cdc0e9">getEffectiveRelocModel</a> (std::optional&lt; Reloc::Model &gt; RM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01d552fbdd044b3e41bb99f905bcccd">LLVMInitializeHexagonTarget</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9001675d305143163d204ed09cc01379">EnableCExtOpt</a>("hexagon-cext", cl::Hidden, cl::init(true), cl::desc("Enable Hexagon constant-extender optimization"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4d9fcf01479ecfef4f598a31e8cdd8">EnableRDFOpt</a>("rdf-opt", cl::Hidden, cl::init(true), cl::desc("Enable RDF-based optimizations"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad885a395876113c89f37e861c08a4b49">RDFFuncBlockLimit</a>("rdf-bb-limit", cl::Hidden, cl::init(1000), cl::desc("Basic block limit for a function for RDF optimizations"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a28353a86a87f2223210d101dce96d">DisableHardwareLoops</a>("disable-hexagon-hwloops", cl::Hidden, cl::desc("Disable Hardware Loops for Hexagon target"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34326d3a10edcef836a3aa95be00f412">DisableAModeOpt</a>("disable-hexagon-amodeopt", cl::Hidden, cl::desc("Disable Hexagon Addressing Mode Optimization"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24853b47ad42af9de33e83f4a569abd3">DisableHexagonCFGOpt</a>("disable-hexagon-cfgopt", cl::Hidden, cl::desc("Disable Hexagon CFG Optimization"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55b4996648faae0cb0d4744fce912f84">DisableHCP</a>("disable-hcp", cl::Hidden, cl::desc("Disable Hexagon constant propagation"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a944c3cce370690247cfec637332b0b8c">DisableHexagonMask</a>("disable-mask", cl::Hidden, cl::desc("Disable Hexagon specific Mask generation pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5958ae17ca05a8a58c734199a9ce4446">DisableStoreWidening</a>("disable-store-widen", cl::Hidden, cl::init(false), cl::desc("Disable store widening"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903ebd851a50d128ca83e72ca0cc9956">DisableLoadWidening</a>("disable-load-widen", cl::Hidden, cl::desc("Disable load widening"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d1799ff5c69c94724dd4b6477c260c5">EnableExpandCondsets</a>("hexagon-expand-condsets", cl::init(true), cl::Hidden, cl::desc("Early expansion of MUX"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab29da7a224120fd6ae08f2569b0f5f45">EnableTfrCleanup</a>("hexagon-tfr-cleanup", cl::init(true), cl::Hidden, cl::desc("Cleanup of TFRs/COPYs"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe512f21fae028ea9c8f4e953ee39318">EnableEarlyIf</a>("hexagon-eif", cl::init(true), cl::Hidden, cl::desc("Enable early if-conversion"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fc797c36adabd3e7775dc15f416933">EnableCopyHoist</a>("hexagon-copy-hoist", cl::init(true), cl::Hidden, cl::ZeroOrMore, cl::desc("Enable Hexagon copy hoisting"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f3fab291c6d76110f406fdf0a45550">EnableGenInsert</a>("hexagon-insert", cl::init(true), cl::Hidden, cl::desc("Generate \"insert\" instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af865f58a1daf96185c508856931924d5">EnableCommGEP</a>("hexagon-commgep", cl::init(true), cl::Hidden, cl::desc("Enable commoning of GEP instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209fddd75f363c5c0edbd0a8313cb6e9">EnableGenExtract</a>("hexagon-extract", cl::init(true), cl::Hidden, cl::desc("Generate \"extract\" instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c9b3518495043b3779f49a6e34b82e">EnableGenMux</a>("hexagon-mux", cl::init(true), cl::Hidden, cl::desc("Enable converting conditional transfers into MUX instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72a98d2b48a2fec0edba6b5022b7b218">EnableGenPred</a>("hexagon-gen-pred", cl::init(true), cl::Hidden, cl::desc("Enable conversion of arithmetic operations to " "predicate instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8b58c4902a22d3c42680cc02287263">EnableLoopPrefetch</a>("hexagon-loop-prefetch", cl::Hidden, cl::desc("Enable loop data prefetch on Hexagon"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab99b217b5d9729f04312e32fe8e7c5f1">DisableHSDR</a>("disable-hsdr", cl::init(false), cl::Hidden, cl::desc("Disable splitting double registers"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb61ae65db622827ad31066a501408c">EnableGenMemAbs</a>("hexagon-mem-abs", cl::init(true), cl::Hidden, cl::desc("Generate absolute set instructions"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5990e7fe7cd7d8096de45e14fa388c50">EnableBitSimplify</a>("hexagon-bit", cl::init(true), cl::Hidden, cl::desc("Bit simplification"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97fecd006eca978f3ffb7a6e1f7a329f">EnableLoopResched</a>("hexagon-loop-resched", cl::init(true), cl::Hidden, cl::desc("Loop rescheduling"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1363328a120c910cc42f4841906b27b7">HexagonNoOpt</a>("hexagon-noopt", cl::init(false), cl::Hidden, cl::desc("Disable backend optimizations"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f02946c2491d6fa95155b316c24ba65">EnableVectorPrint</a>("enable-hexagon-vector-print", cl::Hidden, cl::desc("Enable Hexagon Vector print instr pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80e9b8b56922bfd06ca6835329a76324">EnableVExtractOpt</a>("hexagon-opt-vextract", cl::Hidden, cl::init(true), cl::desc("Enable vextract optimization"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a229a3086c94cd3ee59dd816141e13008">EnableVectorCombine</a>("hexagon-vector-combine", cl::Hidden, cl::init(true), cl::desc("Enable HVX vector combining"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ec53b0fca6016afc5c61981aec2c9b">EnableInitialCFGCleanup</a>("hexagon-initial-cfg-cleanup", cl::Hidden, cl::init(true), cl::desc("Simplify the CFG after atomic expansion pass"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879cc3a727c9ca30b527d05d254a81fe">EnableInstSimplify</a>("hexagon-instsimplify", cl::Hidden, cl::init(true), cl::desc("Enable instsimplify"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92f7572ddcb45a3a9fb9172e91fafd81">HexagonTargetMachineModule</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HexagonTargetMachineModule - Note that this is used on hosts that cannot link in a library unless there are references into the library. <a href="#a92f7572ddcb45a3a9fb9172e91fafd81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineschedregistry">MachineSchedRegistry</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bcdb3d1ee7e3334046cbf2367370c41">SchedCustomRegistry</a>("hexagon", "Run Hexagon's custom scheduler", createVLIWMachineSched)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba71ac83fc0882e97760c16e84ed9599">GET_PASS_REGISTRY</a>&nbsp;&nbsp;&nbsp;"HexagonPassRegistry.def"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae630e66bd51cb0c84874bd406b12f4a3">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c86fdb6a64efb8ec4a59327aa6793">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97a1c5adfbad7cfb551750d9dec6b013">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67c895b5207a31e73cf972bb58ab5aa9">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a613be0a47ad4283b033171c7d91ebce9">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6263fb21d44822c311d528df14c7d1d3">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39f2a031848ee3c43432d32ba6d42300">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a153ed55c08dcea6b7bee890741e2465f">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54aaec23a0af37818d0b521b9c7cd10d">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bee684ed42fc73cd9184c6c924b57c">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70051016d8672632182efe9799c4c083">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41d7c2793b719b960a6cf9b5fe2aa4e8">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0ff03a6bb4a70e73fd5083c3679e52">MODULE_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7500ad7948c3ddde5d682816f775f4e1">MODULE_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe799143be34291491c183ed9c0eea7">FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311ebbf608e96c2cf18b6720168da442">FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c129b1a117c00315516028a20df042">LOOP_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6116ae7b86d8db66ba2cf3f1f061ce1">MACHINE_FUNCTION_PASS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7b7a2c70f63ae1138cb04e1479bf2e">MACHINE_FUNCTION_PASS_WITH_PARAMS</a>(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dec599234592c714174fee76a88c710">MODULE_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2873b9291c09bb8bac44be66f5f79b0c">FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b4a11b77c533a402e27bd36033e5f5">FUNCTION_ALIAS_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c6fd949900e2be4f909ae96a018bef9">LOOP_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304fa0b7b45d6b32d5742c05f852b1f2">MACHINE_FUNCTION_ANALYSIS</a>(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
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

### createVLIWMachineSched() {#aab77d912a7ea86c5c77bc6eacb9adca6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs * createVLIWMachineSched (<a href="/web-llvm/docs/api/structs/llvm/machineschedcontext">MachineSchedContext</a> * C)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a2002164aea6fabe20598e0526746b1fa">llvm::ScheduleDAGMI::addMutation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae82d653cf862c571ba16050a19426458">llvm::createCopyConstrainDAGMutation</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a348590624c488b04d0f9e227e6c3960e">llvm::ScheduleDAG::TII</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a418bc6d3f660325fa6d5b9fb269add62">llvm::ScheduleDAG::TRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a58ec343bc43cccbc53f1d2ea82ee5e2e">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::createMachineScheduler</a>.</p>

</div>
</div>

### getEffectiveRelocModel() {#a906e08cf722c544eeff0ae4295cdc0e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model getEffectiveRelocModel (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM)</td>
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



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568a2102fa713297236bf4339c5f0bf0f39d">llvm::Reloc::Static</a>.</p>

</div>
</div>

### LLVMInitializeHexagonTarget() {#af01d552fbdd044b3e41bb99f905bcccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_EXTERNAL_VISIBILITY void LLVMInitializeHexagonTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57f539ab05ad50c345d4d4975d0ffd6f">llvm::getTheHexagonTarget</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a654e57c879ed4be177789182dccda5fd">llvm::initializeHexagonBitSimplifyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4f1628d3f3d674c04aaf3568186a61a">llvm::initializeHexagonConstExtendersPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad4de54d7256e8a2b302c5b7b6de2da98">llvm::initializeHexagonConstPropagationPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac0d2fcad7ebe5ec9820173109ebb4b69">llvm::initializeHexagonCopyToCombinePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c94ae61e8df1f05dfc4a719a10b0aac">llvm::initializeHexagonDAGToDAGISelLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ea9b37148c69bf2509658c7cf82bce5">llvm::initializeHexagonEarlyIfConversionPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e913ea892810615f5f560ec4c14f9ee">llvm::initializeHexagonGenMemAbsolutePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6f93c3add0c808a32f092fe13a939c5">llvm::initializeHexagonGenMuxPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec90335b734fccd44f087326d9a6e7a1">llvm::initializeHexagonHardwareLoopsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3ef61d910091126ee6b3cdef595e838">llvm::initializeHexagonLoopIdiomRecognizeLegacyPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c0e7c246d2be9f13e185655e8f7d05f">llvm::initializeHexagonNewValueJumpPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a060bec1c050be063e741b008811c4de9">llvm::initializeHexagonOptAddrModePass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5de82e1150528a8ef77da7dee97ae05c">llvm::initializeHexagonPacketizerPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341d5167cf23585915c9578793ce7218">llvm::initializeHexagonRDFOptPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1e80f5feb206565338c3995dff421c1f">llvm::initializeHexagonSplitDoubleRegsPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89d1c985cc9c722f8d01f71f8df20033">llvm::initializeHexagonVectorCombineLegacyPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ca59b4085f443d7cb8947c9bd3c25d">llvm::initializeHexagonVectorLoopCarriedReuseLegacyPassPass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afd0e3cc3dac4ee81271839198a8a3170">llvm::initializeHexagonVExtractPass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DisableAModeOpt {#a34326d3a10edcef836a3aa95be00f412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableAModeOpt("disable-hexagon-amodeopt", cl::Hidden, cl::desc("Disable Hexagon Addressing Mode Optimization"))</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ab0763413dfa57a881314355bb075ba86">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPostRegAlloc</a>.</p>

</div>
</div>

### DisableHardwareLoops {#a71a28353a86a87f2223210d101dce96d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableHardwareLoops("disable-hexagon-hwloops", cl::Hidden, cl::desc("Disable Hardware Loops for Hexagon target"))</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a383b8a8b877e49abe4c951d6df789d45">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreEmitPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### DisableHCP {#a55b4996648faae0cb0d4744fce912f84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableHCP("disable-hcp", cl::Hidden, cl::desc("Disable Hexagon constant propagation"))</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### DisableHexagonCFGOpt {#a24853b47ad42af9de33e83f4a569abd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableHexagonCFGOpt("disable-hexagon-cfgopt", cl::Hidden, cl::desc("Disable Hexagon CFG Optimization"))</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ab0763413dfa57a881314355bb075ba86">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPostRegAlloc</a>.</p>

</div>
</div>

### DisableHexagonMask {#a944c3cce370690247cfec637332b0b8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableHexagonMask("disable-mask", cl::Hidden, cl::desc("Disable Hexagon specific Mask generation pass"))</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a0c44ce1d16724b00c765ae9cb864ef16">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreSched2</a>.</p>

</div>
</div>

### DisableHSDR {#ab99b217b5d9729f04312e32fe8e7c5f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableHSDR("disable-hsdr", cl::init(false), cl::Hidden, cl::desc("Disable splitting double registers"))</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### DisableLoadWidening {#a903ebd851a50d128ca83e72ca0cc9956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableLoadWidening("disable-load-widen", cl::Hidden, cl::desc("Disable load widening"))</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### DisableStoreWidening {#a5958ae17ca05a8a58c734199a9ce4446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; DisableStoreWidening("disable-store-widen", cl::Hidden, cl::init(false), cl::desc("Disable store widening"))</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableBitSimplify {#a5990e7fe7cd7d8096de45e14fa388c50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableBitSimplify("hexagon-bit", cl::init(true), cl::Hidden, cl::desc("Bit simplification"))</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### EnableCExtOpt {#a9001675d305143163d204ed09cc01379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCExtOpt("hexagon-cext", cl::Hidden, cl::init(true), cl::desc("Enable Hexagon constant-extender optimization"))</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableCommGEP {#af865f58a1daf96185c508856931924d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCommGEP("hexagon-commgep", cl::init(true), cl::Hidden, cl::desc("Enable commoning of GEP instructions"))</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ac93af065c06aa9526f1e7271b510df04">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableCopyHoist {#a12fc797c36adabd3e7775dc15f416933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCopyHoist("hexagon-copy-hoist", cl::init(true), cl::Hidden, cl::ZeroOrMore, cl::desc("Enable Hexagon copy hoisting"))</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableEarlyIf {#afe512f21fae028ea9c8f4e953ee39318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableEarlyIf("hexagon-eif", cl::init(true), cl::Hidden, cl::desc("Enable early if-conversion"))</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### EnableExpandCondsets {#a0d1799ff5c69c94724dd4b6477c260c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableExpandCondsets("hexagon-expand-condsets", cl::init(true), cl::Hidden, cl::desc("Early expansion of MUX"))</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableGenExtract {#a209fddd75f363c5c0edbd0a8313cb6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGenExtract("hexagon-extract", cl::init(true), cl::Hidden, cl::desc("Generate \"extract\" instructions"))</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ac93af065c06aa9526f1e7271b510df04">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableGenInsert {#af5f3fab291c6d76110f406fdf0a45550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGenInsert("hexagon-insert", cl::init(true), cl::Hidden, cl::desc("Generate \"insert\" instructions"))</td>
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



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### EnableGenMemAbs {#a7eb61ae65db622827ad31066a501408c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGenMemAbs("hexagon-mem-abs", cl::init(true), cl::Hidden, cl::desc("Generate absolute set instructions"))</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableGenMux {#a22c9b3518495043b3779f49a6e34b82e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGenMux("hexagon-mux", cl::init(true), cl::Hidden, cl::desc("Enable converting conditional transfers into MUX instructions"))</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a383b8a8b877e49abe4c951d6df789d45">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### EnableGenPred {#a72a98d2b48a2fec0edba6b5022b7b218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableGenPred("hexagon-gen-pred", cl::init(true), cl::Hidden, cl::desc("Enable conversion of arithmetic operations to " "predicate instructions"))</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### EnableInitialCFGCleanup {#ac7ec53b0fca6016afc5c61981aec2c9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableInitialCFGCleanup("hexagon-initial-cfg-cleanup", cl::Hidden, cl::init(true), cl::desc("Simplify the CFG after atomic expansion pass"))</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ac93af065c06aa9526f1e7271b510df04">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableInstSimplify {#a879cc3a727c9ca30b527d05d254a81fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableInstSimplify("hexagon-instsimplify", cl::Hidden, cl::init(true), cl::desc("Enable instsimplify"))</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ac93af065c06aa9526f1e7271b510df04">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableLoopPrefetch {#aef8b58c4902a22d3c42680cc02287263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopPrefetch("hexagon-loop-prefetch", cl::Hidden, cl::desc("Enable loop data prefetch on Hexagon"))</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>

</div>
</div>

### EnableLoopResched {#a97fecd006eca978f3ffb7a6e1f7a329f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableLoopResched("hexagon-loop-resched", cl::init(true), cl::Hidden, cl::desc("Loop rescheduling"))</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### EnableRDFOpt {#a8d4d9fcf01479ecfef4f598a31e8cdd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableRDFOpt("rdf-opt", cl::Hidden, cl::init(true), cl::desc("Enable RDF-based optimizations"))</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ab0763413dfa57a881314355bb075ba86">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPostRegAlloc</a>.</p>

</div>
</div>

### EnableTfrCleanup {#ab29da7a224120fd6ae08f2569b0f5f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableTfrCleanup("hexagon-tfr-cleanup", cl::init(true), cl::Hidden, cl::desc("Cleanup of TFRs/COPYs"))</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a6b527c478a68c3620d05e93db5ef254a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreRegAlloc</a>.</p>

</div>
</div>

### EnableVectorCombine {#a229a3086c94cd3ee59dd816141e13008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableVectorCombine("hexagon-vector-combine", cl::Hidden, cl::init(true), cl::desc("Enable HVX vector combining"))</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#ac93af065c06aa9526f1e7271b510df04">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addIRPasses</a>.</p>

</div>
</div>

### EnableVectorPrint {#a5f02946c2491d6fa95155b316c24ba65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableVectorPrint("enable-hexagon-vector-print", cl::Hidden, cl::desc("Enable Hexagon Vector print instr pass"))</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a383b8a8b877e49abe4c951d6df789d45">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addPreEmitPass</a>.</p>

</div>
</div>

### EnableVExtractOpt {#a80e9b8b56922bfd06ca6835329a76324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableVExtractOpt("hexagon-opt-vextract", cl::Hidden, cl::init(true), cl::desc("Enable vextract optimization"))</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagontargetmachine-cpp-/hexagonpassconfig/#a62fb646c12db92e5eb16b019f4a9364a">anonymous{HexagonTargetMachine.cpp}::HexagonPassConfig::addInstSelector</a>.</p>

</div>
</div>

### HexagonNoOpt {#a1363328a120c910cc42f4841906b27b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; HexagonNoOpt("hexagon-noopt", cl::init(false), cl::Hidden, cl::desc("Disable backend optimizations"))</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagontargetmachine/#aaba049307055dcc9ea7de0eb29f0d5b3">llvm::HexagonTargetMachine::HexagonTargetMachine</a>.</p>

</div>
</div>

### HexagonTargetMachineModule {#a92f7572ddcb45a3a9fb9172e91fafd81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HexagonTargetMachineModule = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>HexagonTargetMachineModule - Note that this is used on hosts that cannot link in a library unless there are references into the library.</p>


<p>In particular, it seems that it is not possible to get things to work on Win32 without this. Though it is unused, do not remove it.</p>


<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>

</div>
</div>

### RDFFuncBlockLimit {#ad885a395876113c89f37e861c08a4b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; RDFFuncBlockLimit("rdf-bb-limit", cl::Hidden, cl::init(1000), cl::desc("Basic block limit for a function for RDF optimizations"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>

</div>
</div>

### SchedCustomRegistry {#a6bcdb3d1ee7e3334046cbf2367370c41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSchedRegistry SchedCustomRegistry("hexagon", "Run Hexagon's custom scheduler", createVLIWMachineSched)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ADD\_CLASS\_PASS\_TO\_PASS\_NAME {#a785883ec0154b6773dd0c47b13588a1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_CLASS_PASS_TO_PASS_NAME(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(decltype(CREATE_PASS)<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">::name</a>(), NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file TargetPassRegistry.inc.</p>

</div>
</div>

### ADD\_CLASS\_PASS\_TO\_PASS\_NAME\_WITH\_PARAMS {#a30af641d5b42457b0cb49ad7eeeba6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS(NAME, CLASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#ad4d247df65c12507f447383be37d7ccb">PIC</a>-&gt;addClassToPassName(CLASS, NAME);</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file TargetPassRegistry.inc.</p>

</div>
</div>

### ADD\_PASS {#a7e81816a66f7a306d304777ce3b1d3dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    PM.addPass(CREATE_PASS);                                                   \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 78 of file TargetPassRegistry.inc.</p>

</div>
</div>

### ADD\_PASS\_WITH\_PARAMS {#a60cfccc5fc706d773a18ba77db9c807f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ADD_PASS_WITH_PARAMS(NAME, CREATE_PASS, PARSER)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (PassBuilder::checkParametrizedPassName(Name, NAME)) {                    \
    auto Params = PassBuilder::parsePassParameters(PARSER, Name, NAME);        \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!Params) {                                                             \
      errs() &lt;&lt; NAME ": " &lt;&lt; <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/mirparser/miparser-cpp/#a7206d13e3a41147c732071c64bd84825">toString</a>(Params.takeError()) &lt;&lt; '\n';             \
      return false;                                                            \
    }                                                                          \
    PM.addPass(CREATE_PASS(Params.get()));                                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 84 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a613be0a47ad4283b033171c7d91ebce9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ALIAS\_ANALYSIS {#a53b4a11b77c533a402e27bd36033e5f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ALIAS_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Name == NAME) {                                                          \
    AM.registerFunctionAnalysis&lt;                                               \
        std::remove_reference_t&lt;decltype(CREATE_PASS)&gt;&gt;();                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 172 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a67c895b5207a31e73cf972bb58ab5aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_ANALYSIS {#a2873b9291c09bb8bac44be66f5f79b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS {#a6263fb21d44822c311d528df14c7d1d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS {#a2fe799143be34291491c183ed9c0eea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a39f2a031848ee3c43432d32ba6d42300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file TargetPassRegistry.inc.</p>

</div>
</div>

### FUNCTION\_PASS\_WITH\_PARAMS {#a311ebbf608e96c2cf18b6720168da442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file TargetPassRegistry.inc.</p>

</div>
</div>

### GET\_PASS\_REGISTRY {#aba71ac83fc0882e97760c16e84ed9599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_PASS_REGISTRY&nbsp;&nbsp;&nbsp;"HexagonPassRegistry.def"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp">HexagonTargetMachine.cpp</a>.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a153ed55c08dcea6b7bee890741e2465f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file TargetPassRegistry.inc.</p>

</div>
</div>

### LOOP\_ANALYSIS {#a4c6fd949900e2be4f909ae96a018bef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file TargetPassRegistry.inc.</p>

</div>
</div>

### LOOP\_PASS {#a54aaec23a0af37818d0b521b9c7cd10d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file TargetPassRegistry.inc.</p>

</div>
</div>

### LOOP\_PASS {#a23c129b1a117c00315516028a20df042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LOOP_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#ae8bee684ed42fc73cd9184c6c924b57c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_ANALYSIS {#a304fa0b7b45d6b32d5742c05f852b1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#a70051016d8672632182efe9799c4c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS {#ac6116ae7b86d8db66ba2cf3f1f061ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a41d7c2793b719b960a6cf9b5fe2aa4e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MACHINE\_FUNCTION\_PASS\_WITH\_PARAMS {#a0e7b7a2c70f63ae1138cb04e1479bf2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MACHINE_FUNCTION_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_ANALYSIS {#ae630e66bd51cb0c84874bd406b12f4a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_ANALYSIS {#a0dec599234592c714174fee76a88c710}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_ANALYSIS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  AM.registerPass([&amp;] { return CREATE_PASS; });</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS {#a582c86fdb6a64efb8ec4a59327aa6793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a785883ec0154b6773dd0c47b13588a1a">ADD_CLASS_PASS_TO_PASS_NAME</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS {#a0b0ff03a6bb4a70e73fd5083c3679e52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS(NAME, CREATE_PASS)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a7e81816a66f7a306d304777ce3b1d3dc">ADD_PASS</a>(NAME, CREATE_PASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a97a1c5adfbad7cfb551750d9dec6b013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a30af641d5b42457b0cb49ad7eeeba6d3">ADD_CLASS_PASS_TO_PASS_NAME_WITH_PARAMS</a>(NAME, CLASS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file TargetPassRegistry.inc.</p>

</div>
</div>

### MODULE\_PASS\_WITH\_PARAMS {#a7500ad7948c3ddde5d682816f775f4e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODULE_PASS_WITH_PARAMS(NAME, CLASS, CREATE_PASS, PARSER, PARAMS)&nbsp;&nbsp;&nbsp;  <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#a60cfccc5fc706d773a18ba77db9c807f">ADD_PASS_WITH_PARAMS</a>(NAME, CREATE_PASS, PARSER)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file TargetPassRegistry.inc.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
