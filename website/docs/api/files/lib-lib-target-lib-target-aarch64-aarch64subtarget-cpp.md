---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64Subtarget.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-h">AArch64InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pbqpregalloc-h">AArch64PBQPRegAlloc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-h">AArch64TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-h">GISel/AArch64CallLowering.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64legalizerinfo-h">GISel/AArch64LegalizerInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64registerbankinfo-h">GISel/AArch64RegisterBankInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">MCTargetDesc/AArch64AddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/instructionselect-h">llvm/CodeGen/GlobalISel/InstructionSelect.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineframeinfo-h">llvm/CodeGen/MachineFrameInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinescheduler-h">llvm/CodeGen/MachineScheduler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/siphash-h">llvm/Support/SipHash.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/aarch64targetparser-h">llvm/TargetParser/AArch64TargetParser.h</a>"
#include "AArch64GenSubtargetInfo.inc"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab43de97739917d586616937123ef0fbf">EnableEarlyIfConvert</a>("aarch64-early-ifcvt", cl::desc("Enable the early if " "converter pass"), cl::init(true), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14e78c6fbaa1fcab5d5fa0ad8f7c46d8">UseAddressTopByteIgnored</a>("aarch64-use-tbi", cl::desc("Assume that top byte of " "an address is ignored"), cl::init(false), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47546b8467e7d7c6556f998b034fe863">MachOUseNonLazyBind</a>("aarch64-macho-enable-nonlazybind", cl::desc("Call nonlazybind functions via direct GOT load for Mach-O"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59a2062ef349882aa9c631277e37a74">UseAA</a>("aarch64-use-aa", cl::init(true), cl::desc("Enable the use of AA during codegen."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af81369e40408bddbf3c1c4b06ebc48c4">OverrideVectorInsertExtractBaseCost</a>("aarch64-insert-extract-base-cost", cl::desc("Base cost of vector insert/extract element"), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af563183167da8f02154765192c6449ac">ReservedRegsForRA</a>("reserve-regs-for-regalloc", cl::desc("Reserve physical " "registers, so they can't be used by register allocator. " "Should only be used for testing register allocator."), cl::CommaSeparated, cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; AArch64PAuth::AuthCheckMethod &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a702a1c7df390854ca66dd8b7607c3844">AuthenticatedLRCheckMethod</a>("aarch64-authenticated-lr-check-method", cl::Hidden, cl::desc("Override the variant of check applied " "to authenticated LR during tail call"), cl::values(AUTH_CHECK_METHOD_CL_VALUES_LR))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68dccbf7c5fedf14268ce50cc184da25">AArch64MinimumJumpTableEntries</a>("aarch64-min-jump-table-entries", cl::init(13), cl::Hidden, cl::desc("Set minimum number of entries to use a jump table on AArch64"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad210c499e848202f1fabb9fdddc89387">AArch64StreamingHazardSize</a>("aarch64-streaming-hazard-size", cl::desc("Hazard size for streaming mode memory accesses. 0 = disabled."), cl::init(0), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/alias">cl::alias</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae982d3bac8da9651deeec0d15d9e2de3">AArch64StreamingStackHazardSize</a>("aarch64-stack-hazard-size", cl::desc("alias for -aarch64-streaming-hazard-size"), cl::aliasopt(AArch64StreamingHazardSize))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af522e637a0ed824a6ecabe4814c0c03b">EnableZPRPredicateSpills</a>("aarch64-enable-zpr-predicate-spills", cl::init(false), cl::Hidden, cl::desc("Enables spilling/reloading SVE predicates as data vectors (ZPRs)"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822c5f2181439c6942d190206300928d">EnableSubregLivenessTracking</a>("aarch64-enable-subreg-liveness-tracking", cl::init(false), cl::Hidden, cl::desc("Enable subreg liveness tracking"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea447642b4be61e253ef3add45801812">UseScalarIncVL</a>("sve-use-scalar-inc-vl", cl::init(false), cl::Hidden, cl::desc("Prefer add+cnt over addvl/inc/dec"))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-subtarget"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e319f7bba8b140ee2d876cc3f8308b">GET_SUBTARGETINFO_CTOR</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9edcf2eb5fb8161f71f0b6540ad9cf95">GET_SUBTARGETINFO_TARGET_DESC</a></td>
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

## Variables

### AArch64MinimumJumpTableEntries {#a68dccbf7c5fedf14268ce50cc184da25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; AArch64MinimumJumpTableEntries("aarch64-min-jump-table-entries", cl::init(13), cl::Hidden, cl::desc("Set minimum number of entries to use a jump table on AArch64"))</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### AArch64StreamingHazardSize {#ad210c499e848202f1fabb9fdddc89387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; AArch64StreamingHazardSize("aarch64-streaming-hazard-size", cl::desc("Hazard size for streaming mode memory accesses. 0 = disabled."), cl::init(0), cl::Hidden)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a033ed3ccb4d48ca276a60b87127b344d">llvm::AArch64Subtarget::AArch64Subtarget</a>.</p>

</div>
</div>

### AArch64StreamingStackHazardSize {#ae982d3bac8da9651deeec0d15d9e2de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::alias AArch64StreamingStackHazardSize("aarch64-stack-hazard-size", cl::desc("alias for -aarch64-streaming-hazard-size"), cl::aliasopt(AArch64StreamingHazardSize))</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### AuthenticatedLRCheckMethod {#a702a1c7df390854ca66dd8b7607c3844}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; AArch64PAuth::AuthCheckMethod &gt; AuthenticatedLRCheckMethod("aarch64-authenticated-lr-check-method", cl::Hidden, cl::desc("Override the variant of check applied " "to authenticated LR during tail call"), cl::values(AUTH_CHECK_METHOD_CL_VALUES_LR))</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#af11871b65a6cfc7ce8fc20403e18ab40">llvm::AArch64Subtarget::getAuthenticatedLRCheckMethod</a>.</p>

</div>
</div>

### EnableEarlyIfConvert {#ab43de97739917d586616937123ef0fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableEarlyIfConvert("aarch64-early-ifcvt", cl::desc("Enable the early if " "converter pass"), cl::init(true), cl::Hidden)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a4f1b97ad9a816b42a7f12ca65c76313d">llvm::AArch64Subtarget::enableEarlyIfConversion</a>.</p>

</div>
</div>

### EnableSubregLivenessTracking {#a822c5f2181439c6942d190206300928d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableSubregLivenessTracking("aarch64-enable-subreg-liveness-tracking", cl::init(false), cl::Hidden, cl::desc("Enable subreg liveness tracking"))</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a033ed3ccb4d48ca276a60b87127b344d">llvm::AArch64Subtarget::AArch64Subtarget</a>.</p>

</div>
</div>

### EnableZPRPredicateSpills {#af522e637a0ed824a6ecabe4814c0c03b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableZPRPredicateSpills("aarch64-enable-zpr-predicate-spills", cl::init(false), cl::Hidden, cl::desc( "Enables spilling/reloading SVE predicates as data vectors (ZPRs)"))</td>
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



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#acc204cbb4d2c7b9c5364d89a40deea5b">llvm::AArch64Subtarget::getHwModeSet</a>.</p>

</div>
</div>

### MachOUseNonLazyBind {#a47546b8467e7d7c6556f998b034fe863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; MachOUseNonLazyBind("aarch64-macho-enable-nonlazybind", cl::desc("Call nonlazybind functions via direct GOT load for Mach-O"), cl::Hidden)</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a61b99558b55ac0e86169e5b7eb6ad193">llvm::AArch64Subtarget::classifyGlobalFunctionReference</a>.</p>

</div>
</div>

### OverrideVectorInsertExtractBaseCost {#af81369e40408bddbf3c1c4b06ebc48c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; OverrideVectorInsertExtractBaseCost("aarch64-insert-extract-base-cost", cl::desc("Base cost of vector insert/extract element"), cl::Hidden)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a59fa8edbdb0dcf971dccf48d88b36dab">llvm::AArch64Subtarget::getVectorInsertExtractBaseCost</a>.</p>

</div>
</div>

### ReservedRegsForRA {#af563183167da8f02154765192c6449ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; ReservedRegsForRA("reserve-regs-for-regalloc", cl::desc("Reserve physical " "registers, so they can't be used by register allocator. " "Should only be used for testing register allocator."), cl::CommaSeparated, cl::Hidden)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a033ed3ccb4d48ca276a60b87127b344d">llvm::AArch64Subtarget::AArch64Subtarget</a>.</p>

</div>
</div>

### UseAA {#ad59a2062ef349882aa9c631277e37a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseAA("aarch64-use-aa", cl::init(true), cl::desc("Enable the use of AA during codegen."))</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a64cb9803bb305e47d2e8ef2e8994aae0">llvm::AArch64Subtarget::useAA</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnsubtarget/#a9f0c2a9bd6fbb4b4f778c62d04098b3b">llvm::GCNSubtarget::useAA</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchsubtarget/#a5750b47b8dcf04eb6ee925d408dbe0fb">llvm::LoongArchSubtarget::useAA</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvsubtarget/#a982c34f5a3a2e77f3a3bd58937bb3076">llvm::RISCVSubtarget::useAA</a>.</p>

</div>
</div>

### UseAddressTopByteIgnored {#a14e78c6fbaa1fcab5d5fa0ad8f7c46d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseAddressTopByteIgnored("aarch64-use-tbi", cl::desc("Assume that top byte of " "an address is ignored"), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#a76fdf3d877571240f3d86a7a9af696e7">llvm::AArch64Subtarget::supportsAddressTopByteIgnored</a>.</p>

</div>
</div>

### UseScalarIncVL {#aea447642b4be61e253ef3add45801812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseScalarIncVL("sve-use-scalar-inc-vl", cl::init(false), cl::Hidden, cl::desc("Prefer add+cnt over addvl/inc/dec"))</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64subtarget/#ad13aab0ab8d5a27a2669c863ac0cf9c2">llvm::AArch64Subtarget::useScalarIncVL</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-subtarget"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_CTOR {#aa7e319f7bba8b140ee2d876cc3f8308b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_CTOR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

### GET\_SUBTARGETINFO\_TARGET\_DESC {#a9edcf2eb5fb8161f71f0b6540ad9cf95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_SUBTARGETINFO_TARGET_DESC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-cpp">AArch64Subtarget.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
