---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-amdgputargetmachine-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{AMDGPUTargetMachine.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{AMDGPUTargetMachine.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc">SGPRRegisterRegAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/vgprregisterregalloc">VGPRRegisterRegAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/wwmregisterregalloc">WWMRegisterRegAlloc</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig">GCNPassConfig</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d828a500b726dc52f7addecd99e841b">onlyAllocateSGPRs</a> (const TargetRegisterInfo &amp;TRI, const MachineRegisterInfo &amp;MRI, const Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c037340dcf7250f2fa6d36846b9ee3">onlyAllocateVGPRs</a> (const TargetRegisterInfo &amp;TRI, const MachineRegisterInfo &amp;MRI, const Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f4e68d5e8a0046458775daea99506e">onlyAllocateWWMRegs</a> (const TargetRegisterInfo &amp;TRI, const MachineRegisterInfo &amp;MRI, const Register Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592fac5463691d70118200da24479ba0">useDefaultRegisterAllocator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>-{sgpr|wwm|vgpr}-regalloc=... command line option. <a href="#a592fac5463691d70118200da24479ba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66feaf05deb0d9a39e9bc9fce7881e07">initializeDefaultSGPRRegisterAllocatorOnce</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96dfb7cdef3ae777878e041a33fa7f89">initializeDefaultVGPRRegisterAllocatorOnce</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1091d237d4f9dae078a6692ceab27de8">initializeDefaultWWMRegisterAllocatorOnce</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae942b81c260a81b2cf81b9788f59cb6b">createBasicSGPRRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0429d27d16ab48defa81df514029a994">createGreedySGPRRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb3e8091f48c8c17e1f96ccb3ead676">createFastSGPRRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57f9de866311193d4ba37d7e182bdcf">createBasicVGPRRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd5bce724ce98bb3e36e87b5dd6b671">createGreedyVGPRRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa140cd1314a0e3966248ac0e224fe575">createFastVGPRRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51ed018424fca4610ffeb81784d7867">createBasicWWMRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69455adeb51c0fcaec0882663c9b7f2">createGreedyWWMRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b8ffd597d374a6cbce4df9d9e89bdbb">createFastWWMRegisterAllocator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7be802fe94f088ede887edfb8a30085">isLTOPreLink</a> (ThinOrFullLTOPhase Phase)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a726fd49de2283496d73033e546e3572d">InitializeDefaultSGPRRegisterAllocatorFlag</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A dummy default pass factory indicates whether the register allocator is overridden on the command line. <a href="#a726fd49de2283496d73033e546e3572d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb72577d3d0924420158c7937e626f27">InitializeDefaultVGPRRegisterAllocatorFlag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0846d1ad8d8c0ed0713e96fffbe926b0">InitializeDefaultWWMRegisterAllocatorFlag</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc">SGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0f4d12ccc0e0e194553cba4db48bbdf">defaultSGPRRegAlloc</a>("default", "pick SGPR register allocator based on -O option", useDefaultRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#ac256dded4525ec3126d5fc14652cd0b3">SGPRRegisterRegAlloc::FunctionPassCtor</a>, false, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser">RegisterPassParser</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc">SGPRRegisterRegAlloc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d823cd17ed15c9bf1903563c00663d7">SGPRRegAlloc</a>("sgpr-regalloc", cl::Hidden, cl::init(&useDefaultRegisterAllocator), cl::desc("Register allocator to use for SGPRs"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#ac256dded4525ec3126d5fc14652cd0b3">VGPRRegisterRegAlloc::FunctionPassCtor</a>, false, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser">RegisterPassParser</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/vgprregisterregalloc">VGPRRegisterRegAlloc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054b45fe4af0464a3da0a3d7a5f634af">VGPRRegAlloc</a>("vgpr-regalloc", cl::Hidden, cl::init(&useDefaultRegisterAllocator), cl::desc("Register allocator to use for VGPRs"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#ac256dded4525ec3126d5fc14652cd0b3">WWMRegisterRegAlloc::FunctionPassCtor</a>, false, <a href="/web-llvm/docs/api/classes/llvm/registerpassparser">RegisterPassParser</a>&lt; <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/wwmregisterregalloc">WWMRegisterRegAlloc</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ee6114c1dc7b56aade948745b0d2c6">WWMRegAlloc</a>("wwm-regalloc", cl::Hidden, cl::init(&useDefaultRegisterAllocator), cl::desc("Register allocator to use for WWM registers"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc">SGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751923fbf09d02c543e7d175b1306a2c">basicRegAllocSGPR</a>("basic", "basic register allocator", createBasicSGPRRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc">SGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ae5e16f9591bab349b636085867271">greedyRegAllocSGPR</a>("greedy", "greedy register allocator", createGreedySGPRRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/sgprregisterregalloc">SGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee22dcdec87d2239fe98b7b74eb9299b">fastRegAllocSGPR</a>("fast", "fast register allocator", createFastSGPRRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/vgprregisterregalloc">VGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb8baee3a33b37ed3017dd7057c5cfe9">basicRegAllocVGPR</a>("basic", "basic register allocator", createBasicVGPRRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/vgprregisterregalloc">VGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ffdf398f2d73f8ea4962a977d58bf6">greedyRegAllocVGPR</a>("greedy", "greedy register allocator", createGreedyVGPRRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/vgprregisterregalloc">VGPRRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659b5eb78919c4b0e0b468615d4fad5a">fastRegAllocVGPR</a>("fast", "fast register allocator", createFastVGPRRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/wwmregisterregalloc">WWMRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6a5d85bc05c9e725941ad61c5a674d2">basicRegAllocWWMReg</a>("basic", "basic register allocator", createBasicWWMRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/wwmregisterregalloc">WWMRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8bcbb04a6484296cebf6363dff32921">greedyRegAllocWWMReg</a>("greedy", "greedy register allocator", createGreedyWWMRegisterAllocator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/wwmregisterregalloc">WWMRegisterRegAlloc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762923cc941e02542837029ec12ae7d9">fastRegAllocWWMReg</a>("fast", "fast register allocator", createFastWWMRegisterAllocator)</td>
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

### createBasicSGPRRegisterAllocator() {#ae942b81c260a81b2cf81b9788f59cb6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createBasicSGPRRegisterAllocator ()</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa05a4c8f83a169d6f6ca1baededd73ac">llvm::createBasicRegisterAllocator</a> and <a href="#a6d828a500b726dc52f7addecd99e841b">onlyAllocateSGPRs</a>.</p>

</div>
</div>

### createBasicVGPRRegisterAllocator() {#ad57f9de866311193d4ba37d7e182bdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createBasicVGPRRegisterAllocator ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa05a4c8f83a169d6f6ca1baededd73ac">llvm::createBasicRegisterAllocator</a> and <a href="#a85c037340dcf7250f2fa6d36846b9ee3">onlyAllocateVGPRs</a>.</p>

</div>
</div>

### createBasicWWMRegisterAllocator() {#ab51ed018424fca4610ffeb81784d7867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createBasicWWMRegisterAllocator ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa05a4c8f83a169d6f6ca1baededd73ac">llvm::createBasicRegisterAllocator</a> and <a href="#af4f4e68d5e8a0046458775daea99506e">onlyAllocateWWMRegs</a>.</p>

</div>
</div>

### createFastSGPRRegisterAllocator() {#a0eb3e8091f48c8c17e1f96ccb3ead676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createFastSGPRRegisterAllocator ()</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a073a6b54ae729a7dc321b342e8c89a84">llvm::createFastRegisterAllocator</a> and <a href="#a6d828a500b726dc52f7addecd99e841b">onlyAllocateSGPRs</a>.</p>

</div>
</div>

### createFastVGPRRegisterAllocator() {#aa140cd1314a0e3966248ac0e224fe575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createFastVGPRRegisterAllocator ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a073a6b54ae729a7dc321b342e8c89a84">llvm::createFastRegisterAllocator</a> and <a href="#a85c037340dcf7250f2fa6d36846b9ee3">onlyAllocateVGPRs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a378df4e13ead88fb4268b93ec354f169">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createVGPRAllocPass</a>.</p>

</div>
</div>

### createFastWWMRegisterAllocator() {#a0b8ffd597d374a6cbce4df9d9e89bdbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createFastWWMRegisterAllocator ()</td>
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



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a073a6b54ae729a7dc321b342e8c89a84">llvm::createFastRegisterAllocator</a> and <a href="#af4f4e68d5e8a0046458775daea99506e">onlyAllocateWWMRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a20d9cc889332d421bfb591e473db3601">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createWWMRegAllocPass</a>.</p>

</div>
</div>

### createGreedySGPRRegisterAllocator() {#a0429d27d16ab48defa81df514029a994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createGreedySGPRRegisterAllocator ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1e408e746db9cae453eb2799eedc64ce">llvm::createGreedyRegisterAllocator</a> and <a href="#a6d828a500b726dc52f7addecd99e841b">onlyAllocateSGPRs</a>.</p>

</div>
</div>

### createGreedyVGPRRegisterAllocator() {#a0fd5bce724ce98bb3e36e87b5dd6b671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createGreedyVGPRRegisterAllocator ()</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1e408e746db9cae453eb2799eedc64ce">llvm::createGreedyRegisterAllocator</a> and <a href="#a85c037340dcf7250f2fa6d36846b9ee3">onlyAllocateVGPRs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a378df4e13ead88fb4268b93ec354f169">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createVGPRAllocPass</a>.</p>

</div>
</div>

### createGreedyWWMRegisterAllocator() {#ad69455adeb51c0fcaec0882663c9b7f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::createGreedyWWMRegisterAllocator ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1e408e746db9cae453eb2799eedc64ce">llvm::createGreedyRegisterAllocator</a> and <a href="#af4f4e68d5e8a0046458775daea99506e">onlyAllocateWWMRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a20d9cc889332d421bfb591e473db3601">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createWWMRegAllocPass</a>.</p>

</div>
</div>

### initializeDefaultSGPRRegisterAllocatorOnce() {#a66feaf05deb0d9a39e9bc9fce7881e07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUTargetMachine.cpp}::initializeDefaultSGPRRegisterAllocatorOnce ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; SGPRRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a96bb0f039016d0b9999a18a660a38f5b">llvm::RegisterRegAllocBase&lt; SGPRRegisterRegAlloc &gt;::setDefault</a> and <a href="#a4d823cd17ed15c9bf1903563c00663d7">SGPRRegAlloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a22399dbddf111b9bda1744d4c273a593">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createSGPRAllocPass</a>.</p>

</div>
</div>

### initializeDefaultVGPRRegisterAllocatorOnce() {#a96dfb7cdef3ae777878e041a33fa7f89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUTargetMachine.cpp}::initializeDefaultVGPRRegisterAllocatorOnce ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; VGPRRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a96bb0f039016d0b9999a18a660a38f5b">llvm::RegisterRegAllocBase&lt; VGPRRegisterRegAlloc &gt;::setDefault</a> and <a href="#a054b45fe4af0464a3da0a3d7a5f634af">VGPRRegAlloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a378df4e13ead88fb4268b93ec354f169">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createVGPRAllocPass</a>.</p>

</div>
</div>

### initializeDefaultWWMRegisterAllocatorOnce() {#a1091d237d4f9dae078a6692ceab27de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AMDGPUTargetMachine.cpp}::initializeDefaultWWMRegisterAllocatorOnce ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a64385ccd715f0aa796300d361b525e4c">llvm::RegisterRegAllocBase&lt; WWMRegisterRegAlloc &gt;::getDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/registerregallocbase/#a96bb0f039016d0b9999a18a660a38f5b">llvm::RegisterRegAllocBase&lt; WWMRegisterRegAlloc &gt;::setDefault</a> and <a href="#a38ee6114c1dc7b56aade948745b0d2c6">WWMRegAlloc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a20d9cc889332d421bfb591e473db3601">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createWWMRegAllocPass</a>.</p>

</div>
</div>

### isLTOPreLink() {#ac7be802fe94f088ede887edfb8a30085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUTargetMachine.cpp}::isLTOPreLink (<a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49">ThinOrFullLTOPhase</a> Phase)</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49a123c9da36c4ea6b13da1c4dd2e955c3b">llvm::FullLTOPreLink</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64falkorhwpffix-cpp/#a780618ccf661aebc12f8d991d294c950">Phase</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5d737fb4258bb27586a1bffd557fbb49ad94cc56b0a9155d607f2609b0f5c39d3">llvm::ThinLTOPreLink</a>.</p>

</div>
</div>

### onlyAllocateSGPRs() {#a6d828a500b726dc52f7addecd99e841b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateSGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ae942b81c260a81b2cf81b9788f59cb6b">createBasicSGPRRegisterAllocator</a>, <a href="#a0eb3e8091f48c8c17e1f96ccb3ead676">createFastSGPRRegisterAllocator</a>, <a href="#a0429d27d16ab48defa81df514029a994">createGreedySGPRRegisterAllocator</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a22399dbddf111b9bda1744d4c273a593">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createSGPRAllocPass</a>.</p>

</div>
</div>

### onlyAllocateVGPRs() {#a85c037340dcf7250f2fa6d36846b9ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateVGPRs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>


<p>Referenced by <a href="#ad57f9de866311193d4ba37d7e182bdcf">createBasicVGPRRegisterAllocator</a>, <a href="#aa140cd1314a0e3966248ac0e224fe575">createFastVGPRRegisterAllocator</a> and <a href="#a0fd5bce724ce98bb3e36e87b5dd6b671">createGreedyVGPRRegisterAllocator</a>.</p>

</div>
</div>

### onlyAllocateWWMRegs() {#af4f4e68d5e8a0046458775daea99506e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUTargetMachine.cpp}::onlyAllocateWWMRegs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#aa49d47a31cd6d7ac85e7aaa3753ccc48">llvm::SIMachineFunctionInfo::checkFlag</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/virtregflag/#ae40fa7ccf9ef4e1fa2db150e4b74f7a9a31784c8e60845a8b46a9de185dec5645">llvm::AMDGPU::VirtRegFlag::WWM_REG</a>.</p>


<p>Referenced by <a href="#ab51ed018424fca4610ffeb81784d7867">createBasicWWMRegisterAllocator</a>, <a href="#a0b8ffd597d374a6cbce4df9d9e89bdbb">createFastWWMRegisterAllocator</a> and <a href="#ad69455adeb51c0fcaec0882663c9b7f2">createGreedyWWMRegisterAllocator</a>.</p>

</div>
</div>

### useDefaultRegisterAllocator() {#a592fac5463691d70118200da24479ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionPass * anonymous{AMDGPUTargetMachine.cpp}::useDefaultRegisterAllocator ()</td>
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

<p>-{sgpr|wwm|vgpr}-regalloc=... command line option.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a22399dbddf111b9bda1744d4c273a593">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createSGPRAllocPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a378df4e13ead88fb4268b93ec354f169">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createVGPRAllocPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a20d9cc889332d421bfb591e473db3601">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createWWMRegAllocPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### basicRegAllocSGPR {#a751923fbf09d02c543e7d175b1306a2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::basicRegAllocSGPR("basic", "basic register allocator", createBasicSGPRRegisterAllocator)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### basicRegAllocVGPR {#aeb8baee3a33b37ed3017dd7057c5cfe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::basicRegAllocVGPR("basic", "basic register allocator", createBasicVGPRRegisterAllocator)</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### basicRegAllocWWMReg {#ae6a5d85bc05c9e725941ad61c5a674d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WWMRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::basicRegAllocWWMReg("basic", "basic register allocator", createBasicWWMRegisterAllocator)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### defaultSGPRRegAlloc {#ad0f4d12ccc0e0e194553cba4db48bbdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::defaultSGPRRegAlloc("default", "pick SGPR register allocator based on -O option", useDefaultRegisterAllocator)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### fastRegAllocSGPR {#aee22dcdec87d2239fe98b7b74eb9299b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::fastRegAllocSGPR("fast", "fast register allocator", createFastSGPRRegisterAllocator)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### fastRegAllocVGPR {#a659b5eb78919c4b0e0b468615d4fad5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::fastRegAllocVGPR("fast", "fast register allocator", createFastVGPRRegisterAllocator)</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### fastRegAllocWWMReg {#a762923cc941e02542837029ec12ae7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WWMRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::fastRegAllocWWMReg("fast", "fast register allocator", createFastWWMRegisterAllocator)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### greedyRegAllocSGPR {#af5ae5e16f9591bab349b636085867271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::greedyRegAllocSGPR("greedy", "greedy register allocator", createGreedySGPRRegisterAllocator)</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### greedyRegAllocVGPR {#ad7ffdf398f2d73f8ea4962a977d58bf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VGPRRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::greedyRegAllocVGPR("greedy", "greedy register allocator", createGreedyVGPRRegisterAllocator)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### greedyRegAllocWWMReg {#ab8bcbb04a6484296cebf6363dff32921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WWMRegisterRegAlloc anonymous{AMDGPUTargetMachine.cpp}::greedyRegAllocWWMReg("greedy", "greedy register allocator", createGreedyWWMRegisterAllocator)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>

</div>
</div>

### InitializeDefaultSGPRRegisterAllocatorFlag {#a726fd49de2283496d73033e546e3572d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::once_flag anonymous{AMDGPUTargetMachine.cpp}::InitializeDefaultSGPRRegisterAllocatorFlag</td>
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

<p>A dummy default pass factory indicates whether the register allocator is overridden on the command line.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a22399dbddf111b9bda1744d4c273a593">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createSGPRAllocPass</a>.</p>

</div>
</div>

### InitializeDefaultVGPRRegisterAllocatorFlag {#adb72577d3d0924420158c7937e626f27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::once_flag anonymous{AMDGPUTargetMachine.cpp}::InitializeDefaultVGPRRegisterAllocatorFlag</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a378df4e13ead88fb4268b93ec354f169">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createVGPRAllocPass</a>.</p>

</div>
</div>

### InitializeDefaultWWMRegisterAllocatorFlag {#a0846d1ad8d8c0ed0713e96fffbe926b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::once_flag anonymous{AMDGPUTargetMachine.cpp}::InitializeDefaultWWMRegisterAllocatorFlag</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgputargetmachine-cpp-/gcnpassconfig/#a20d9cc889332d421bfb591e473db3601">anonymous{AMDGPUTargetMachine.cpp}::GCNPassConfig::createWWMRegAllocPass</a>.</p>

</div>
</div>

### SGPRRegAlloc {#a4d823cd17ed15c9bf1903563c00663d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; SGPRRegisterRegAlloc::FunctionPassCtor, false, RegisterPassParser&lt; SGPRRegisterRegAlloc &gt; &gt; anonymous{AMDGPUTargetMachine.cpp}::SGPRRegAlloc("sgpr-regalloc", cl::Hidden, cl::init(&amp;useDefaultRegisterAllocator), cl::desc("Register allocator to use for SGPRs"))</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="#a66feaf05deb0d9a39e9bc9fce7881e07">initializeDefaultSGPRRegisterAllocatorOnce</a>.</p>

</div>
</div>

### VGPRRegAlloc {#a054b45fe4af0464a3da0a3d7a5f634af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; VGPRRegisterRegAlloc::FunctionPassCtor, false, RegisterPassParser&lt; VGPRRegisterRegAlloc &gt; &gt; anonymous{AMDGPUTargetMachine.cpp}::VGPRRegAlloc("vgpr-regalloc", cl::Hidden, cl::init(&amp;useDefaultRegisterAllocator), cl::desc("Register allocator to use for VGPRs"))</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="#a96dfb7cdef3ae777878e041a33fa7f89">initializeDefaultVGPRRegisterAllocatorOnce</a>.</p>

</div>
</div>

### WWMRegAlloc {#a38ee6114c1dc7b56aade948745b0d2c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; WWMRegisterRegAlloc::FunctionPassCtor, false, RegisterPassParser&lt; WWMRegisterRegAlloc &gt; &gt; anonymous{AMDGPUTargetMachine.cpp}::WWMRegAlloc("wwm-regalloc", cl::Hidden, cl::init(&amp;useDefaultRegisterAllocator), cl::desc("Register allocator to use for WWM registers"))</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a>.</p>


<p>Referenced by <a href="#a1091d237d4f9dae078a6692ceab27de8">initializeDefaultWWMRegisterAllocatorOnce</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp">AMDGPUTargetMachine.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
