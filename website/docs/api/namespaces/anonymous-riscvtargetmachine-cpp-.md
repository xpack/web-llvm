---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-riscvtargetmachine-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{RISCVTargetMachine.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{RISCVTargetMachine.cpp} { ... }
</div>

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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d9dd0cfe6b9d17e4cb92911dff0e1d">onlyAllocateRVVReg</a> (const TargetRegisterInfo &amp;TRI, const MachineRegisterInfo &amp;MRI, const Register Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb98ca139ad9dfc38c2db160ef607d4f">useDefaultRegisterAllocator</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef90e3afb7602d713d746833d7270d4">initializeDefaultRVVRegisterAllocatorOnce</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1319c367a8c51b6a1daa56c60107ba3">createBasicRVVRegisterAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a284982f3dc9458a0008856a9489c0">createGreedyRVVRegisterAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d212434da967befff1b11fd1def2fda">createFastRVVRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd7d079caa9a4a3fd925c6e3fa00b27">InitializeDefaultRVVRegisterAllocatorFlag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#ac256dded4525ec3126d5fc14652cd0b3">RVVRegisterRegAlloc::FunctionPassCtor</a>, false, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser">RegisterPassParser</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/rvvregisterregalloc">RVVRegisterRegAlloc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4d0b4e691941ea8db7949f86f45a2fc">RVVRegAlloc</a>("riscv-rvv-regalloc", cl::Hidden, cl::init(&useDefaultRegisterAllocator), cl::desc("Register allocator to use for RVV register."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>-riscv-rvv-regalloc=&lt;fast|basic|greedy&gt; command line option. <a href="#ad4d0b4e691941ea8db7949f86f45a2fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/rvvregisterregalloc">RVVRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbaccc6c09bd3988c58a59aaed41d6b5">basicRegAllocRVVReg</a>("basic", "basic register allocator", createBasicRVVRegisterAllocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/rvvregisterregalloc">RVVRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99e7342e98e291af353dbe173db41ff7">greedyRegAllocRVVReg</a>("greedy", "greedy register allocator", createGreedyRVVRegisterAllocator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/rvvregisterregalloc">RVVRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75757bc9e05fa36da712483c4f8f4acd">fastRegAllocRVVReg</a>("fast", "fast register allocator", createFastRVVRegisterAllocator)</td>
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

### createBasicRVVRegisterAllocator() {#ac1319c367a8c51b6a1daa56c60107ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{RISCVTargetMachine.cpp}::createBasicRVVRegisterAllocator ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa05a4c8f83a169d6f6ca1baededd73ac">llvm::createBasicRegisterAllocator</a>, <a href="#ac1319c367a8c51b6a1daa56c60107ba3">createBasicRVVRegisterAllocator</a> and <a href="#a19d9dd0cfe6b9d17e4cb92911dff0e1d">onlyAllocateRVVReg</a>.</p>


<p>Referenced by <a href="#ac1319c367a8c51b6a1daa56c60107ba3">createBasicRVVRegisterAllocator</a>.</p>

</div>
</div>

### createFastRVVRegisterAllocator() {#a0d212434da967befff1b11fd1def2fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{RISCVTargetMachine.cpp}::createFastRVVRegisterAllocator ()</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a073a6b54ae729a7dc321b342e8c89a84">llvm::createFastRegisterAllocator</a>, <a href="#a0d212434da967befff1b11fd1def2fda">createFastRVVRegisterAllocator</a> and <a href="#a19d9dd0cfe6b9d17e4cb92911dff0e1d">onlyAllocateRVVReg</a>.</p>


<p>Referenced by <a href="#a0d212434da967befff1b11fd1def2fda">createFastRVVRegisterAllocator</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a133a13b65f016ae40049bb567e6c1850">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createRVVRegAllocPass</a>.</p>

</div>
</div>

### createGreedyRVVRegisterAllocator() {#a50a284982f3dc9458a0008856a9489c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{RISCVTargetMachine.cpp}::createGreedyRVVRegisterAllocator ()</td>
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



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1e408e746db9cae453eb2799eedc64ce">llvm::createGreedyRegisterAllocator</a>, <a href="#a50a284982f3dc9458a0008856a9489c0">createGreedyRVVRegisterAllocator</a> and <a href="#a19d9dd0cfe6b9d17e4cb92911dff0e1d">onlyAllocateRVVReg</a>.</p>


<p>Referenced by <a href="#a50a284982f3dc9458a0008856a9489c0">createGreedyRVVRegisterAllocator</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a133a13b65f016ae40049bb567e6c1850">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createRVVRegAllocPass</a>.</p>

</div>
</div>

### initializeDefaultRVVRegisterAllocatorOnce() {#a4ef90e3afb7602d713d746833d7270d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{RISCVTargetMachine.cpp}::initializeDefaultRVVRegisterAllocatorOnce ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; RVVRegisterRegAlloc &gt;::getDefault</a>, <a href="#a4ef90e3afb7602d713d746833d7270d4">initializeDefaultRVVRegisterAllocatorOnce</a>, <a href="#ad4d0b4e691941ea8db7949f86f45a2fc">RVVRegAlloc</a> and <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a96bb0f039016d0b9999a18a660a38f5b">llvm::RegisterRegAllocBase&lt; RVVRegisterRegAlloc &gt;::setDefault</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a133a13b65f016ae40049bb567e6c1850">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createRVVRegAllocPass</a> and <a href="#a4ef90e3afb7602d713d746833d7270d4">initializeDefaultRVVRegisterAllocatorOnce</a>.</p>

</div>
</div>

### onlyAllocateRVVReg() {#a19d9dd0cfe6b9d17e4cb92911dff0e1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{RISCVTargetMachine.cpp}::onlyAllocateRVVReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a6b0e6be6a451881260fcd7f29b7fb4fc">llvm::RISCVRegisterInfo::isRVVRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="#a19d9dd0cfe6b9d17e4cb92911dff0e1d">onlyAllocateRVVReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ac1319c367a8c51b6a1daa56c60107ba3">createBasicRVVRegisterAllocator</a>, <a href="#a0d212434da967befff1b11fd1def2fda">createFastRVVRegisterAllocator</a>, <a href="#a50a284982f3dc9458a0008856a9489c0">createGreedyRVVRegisterAllocator</a> and <a href="#a19d9dd0cfe6b9d17e4cb92911dff0e1d">onlyAllocateRVVReg</a>.</p>

</div>
</div>

### useDefaultRegisterAllocator() {#abb98ca139ad9dfc38c2db160ef607d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{RISCVTargetMachine.cpp}::useDefaultRegisterAllocator ()</td>
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



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a133a13b65f016ae40049bb567e6c1850">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createRVVRegAllocPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### basicRegAllocRVVReg {#abbaccc6c09bd3988c58a59aaed41d6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RVVRegisterRegAlloc anonymous{RISCVTargetMachine.cpp}::basicRegAllocRVVReg("basic", "basic register allocator", createBasicRVVRegisterAllocator)</td>
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



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### fastRegAllocRVVReg {#a75757bc9e05fa36da712483c4f8f4acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RVVRegisterRegAlloc anonymous{RISCVTargetMachine.cpp}::fastRegAllocRVVReg("fast", "fast register allocator", createFastRVVRegisterAllocator)</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### greedyRegAllocRVVReg {#a99e7342e98e291af353dbe173db41ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RVVRegisterRegAlloc anonymous{RISCVTargetMachine.cpp}::greedyRegAllocRVVReg("greedy", "greedy register allocator", createGreedyRVVRegisterAllocator)</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>

</div>
</div>

### InitializeDefaultRVVRegisterAllocatorFlag {#a6bd7d079caa9a4a3fd925c6e3fa00b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::once_flag anonymous{RISCVTargetMachine.cpp}::InitializeDefaultRVVRegisterAllocatorFlag</td>
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



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a133a13b65f016ae40049bb567e6c1850">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::createRVVRegAllocPass</a>.</p>

</div>
</div>

### RVVRegAlloc {#ad4d0b4e691941ea8db7949f86f45a2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; RVVRegisterRegAlloc::FunctionPassCtor, false, RegisterPassParser&lt; RVVRegisterRegAlloc &gt; &gt; anonymous{RISCVTargetMachine.cpp}::RVVRegAlloc("riscv-rvv-regalloc", cl::Hidden, cl::init(&amp;useDefaultRegisterAllocator), cl::desc("Register allocator to use for RVV register."))</td>
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

<p>-riscv-rvv-regalloc=&lt;fast|basic|greedy&gt; command line option.</p>


<p>This option could designate the rvv register allocator only. For example: -riscv-rvv-regalloc=basic</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="#a4ef90e3afb7602d713d746833d7270d4">initializeDefaultRVVRegisterAllocatorOnce</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp">RISCVTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
