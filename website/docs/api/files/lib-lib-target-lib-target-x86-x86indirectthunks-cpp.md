---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86IndirectThunks.cpp` File Reference

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> that injects an MI thunk that is used to lower indirect calls in a way that prevents speculation on some x86 processors and can be used to mitigate security vulnerabilities due to targeted speculative execution and side channels such as CVE-2017-5715. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86-h">X86.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrbuilder-h">X86InstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86subtarget-h">X86Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/indirectthunks-h">llvm/CodeGen/IndirectThunks.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/target/targetmachine-h">llvm/Target/TargetMachine.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86indirectthunks-cpp-">anonymous{X86IndirectThunks.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter">RetpolineThunkInserter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/lvithunkinserter">LVIThunkInserter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86indirectthunks-cpp-/x86indirectthunks">X86IndirectThunks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e438d35f6d58adbb098c9fbbb817ec6">RetpolineNamePrefix</a>[] = "__llvm_retpoline_"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff0b554e41059ddc0d2282679cf781b4">R11RetpolineName</a>[] = "__llvm_retpoline_r11"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df2f9102a92dfd1ac8a5fc8f02bd09d">EAXRetpolineName</a>[] = "__llvm_retpoline_eax"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0696626dd7cf2894ccc000837ace9eef">ECXRetpolineName</a>[] = "__llvm_retpoline_ecx"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5083e9b29ac47ff6c161b99dba4025a1">EDXRetpolineName</a>[] = "__llvm_retpoline_edx"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca13d5294038c79f499a0d507ab920d">EDIRetpolineName</a>[] = "__llvm_retpoline_edi"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50348bdf14695078f4f46a67a1d11c94">LVIThunkNamePrefix</a>[] = "__llvm_lvi_thunk_"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef912735ccb39752d082b3ab7da0c72">R11LVIThunkName</a>[] = "__llvm_lvi_thunk_r11"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"x86-retpoline-thunks"</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> that injects an MI thunk that is used to lower indirect calls in a way that prevents speculation on some x86 processors and can be used to mitigate security vulnerabilities due to targeted speculative execution and side channels such as CVE-2017-5715.</p>


<p>Currently supported thunks include:</p>


<ul class="doxyList ">
<li>Retpoline – A RET-implemented trampoline that lowers indirect calls</li>
<li>LVI Thunk – A CALL/JMP-implemented thunk that forces load serialization before making an indirect call/jump</li>
</ul>

<p>Note that the reason that this is implemented as a <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> and not a <a href="/web-llvm/docs/api/classes/llvm/modulepass">ModulePass</a> is that ModulePasses at this point in the LLVM <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> pipeline serialize all transformations, which can consume lots of memory.</p>


<p>TODO(chandlerc): All of this code could use better comments and documentation.</p>


<div class="doxySectionDef">

## Variables

### EAXRetpolineName {#a6df2f9102a92dfd1ac8a5fc8f02bd09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char EAXRetpolineName[] = "__llvm_retpoline_eax"</td>
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



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>.</p>

</div>
</div>

### ECXRetpolineName {#a0696626dd7cf2894ccc000837ace9eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char ECXRetpolineName[] = "__llvm_retpoline_ecx"</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>.</p>

</div>
</div>

### EDIRetpolineName {#a4ca13d5294038c79f499a0d507ab920d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char EDIRetpolineName[] = "__llvm_retpoline_edi"</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>.</p>

</div>
</div>

### EDXRetpolineName {#a5083e9b29ac47ff6c161b99dba4025a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char EDXRetpolineName[] = "__llvm_retpoline_edx"</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>.</p>

</div>
</div>

### LVIThunkNamePrefix {#a50348bdf14695078f4f46a67a1d11c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char LVIThunkNamePrefix[] = "__llvm_lvi_thunk_"</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/lvithunkinserter/#ab98680449fcd669cdc8699022cecae9d">anonymous{X86IndirectThunks.cpp}::LVIThunkInserter::getThunkPrefix</a>.</p>

</div>
</div>

### R11LVIThunkName {#aeef912735ccb39752d082b3ab7da0c72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char R11LVIThunkName[] = "__llvm_lvi_thunk_r11"</td>
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



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/lvithunkinserter/#a10eb4a85b60b32c52028dcb8a4623eb6">anonymous{X86IndirectThunks.cpp}::LVIThunkInserter::insertThunks</a>.</p>

</div>
</div>

### R11RetpolineName {#aff0b554e41059ddc0d2282679cf781b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char R11RetpolineName[] = "__llvm_retpoline_r11"</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a623777b0f29b96919b50ce21c13aa6ae">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::insertThunks</a>.</p>

</div>
</div>

### RetpolineNamePrefix {#a0e438d35f6d58adbb098c9fbbb817ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char RetpolineNamePrefix[] = "__llvm_retpoline_"</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#a3fc820b601d5504e99d1e1769f96c32f">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::getThunkPrefix</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"x86-retpoline-thunks"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectthunks-cpp">X86IndirectThunks.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
