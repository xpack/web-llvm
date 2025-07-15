---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/webassembly/webassemblysetp2alignoperands-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `WebAssemblySetP2AlignOperands.cpp` File Reference

<p>This file sets the p2align operands on load and store instructions. <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-h">MCTargetDesc/WebAssemblyMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassembly-h">WebAssembly.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyinstrinfo-h">WebAssemblyInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinememoperand-h">llvm/CodeGen/MachineMemOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-webassemblysetp2alignoperands-cpp-">anonymous{WebAssemblySetP2AlignOperands.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands">WebAssemblySetP2AlignOperands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f630c46c25fe39a0dd0b5329ac34eb4">INITIALIZE_PASS</a> (WebAssemblySetP2AlignOperands, DEBUG_TYPE, "Set the p2align operands for WebAssembly loads and stores", false, false) FunctionPass *llvm</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863a657b356a9f8556dcf310afe02c00">rewriteP2Align</a> (MachineInstr &amp;MI, unsigned OperandNo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"wasm-set-p2align-operands"</td>
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

<p>This file sets the p2align operands on load and store instructions.</p>

<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS() {#a2f630c46c25fe39a0dd0b5329ac34eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (WebAssemblySetP2AlignOperands, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Set the p2align operands <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> WebAssembly <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonloadstorewidening-cpp/#a5414f76815c8f01cd360c99ff6fb27a7">loads</a> and stores", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblysetp2alignoperands-cpp">WebAssemblySetP2AlignOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9b5102a65a75df00b435532bc0f5f7e1">llvm::createWebAssemblySetP2AlignOperands</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands/#abc7f99ab82479df78f317d8587ebadbd">anonymous{WebAssemblySetP2AlignOperands.cpp}::WebAssemblySetP2AlignOperands::WebAssemblySetP2AlignOperands</a>.</p>

</div>
</div>

### rewriteP2Align() {#a863a657b356a9f8556dcf310afe02c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void rewriteP2Align (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OperandNo)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblysetp2alignoperands-cpp">WebAssemblySetP2AlignOperands.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a2a5d29a901287f6b88bf88e4d812f625">llvm::WebAssembly::GetDefaultP2Align</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad82de9da62635df78a534de0f16c1129">llvm::Log2</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#aa5fb9c8405de3efed868f5de2d0ed4e8a4f1b1da70524bd210612cfff4dba4834">llvm::WebAssembly::OPERAND_P2ALIGN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-webassemblysetp2alignoperands-cpp-/webassemblysetp2alignoperands/#aa0150e2afe7a04001d1bbfc2ea7f4e76">anonymous{WebAssemblySetP2AlignOperands.cpp}::WebAssemblySetP2AlignOperands::runOnMachineFunction</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"wasm-set-p2align-operands"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblysetp2alignoperands-cpp">WebAssemblySetP2AlignOperands.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
