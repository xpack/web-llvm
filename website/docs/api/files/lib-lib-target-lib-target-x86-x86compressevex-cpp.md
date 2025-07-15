---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86CompressEVEX.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">MCTargetDesc/X86BaseInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86-h">X86.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86subtarget-h">X86Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstr-h">llvm/CodeGen/MachineInstr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoperand-h">llvm/CodeGen/MachineOperand.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcinstrdesc-h">llvm/MC/MCInstrDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include &lt;atomic&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
#include "X86GenInstrMapping.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-x86compressevex-cpp-">anonymous{X86CompressEVEX.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86compressevex-cpp-/compressevexpass">CompressEVEXPass</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc3f396ced2d97e9feb5f89e6733457">usesExtendedRegister</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fade9b6e8aab907e81b8efabc46c8d4">performCustomAdjustments</a> (MachineInstr &amp;MI, unsigned NewOpc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a> (MachineInstr &amp;MI, const X86Subtarget &amp;ST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14ab6af71c08308e021a231c619495e5">COMP_EVEX_DESC</a>&nbsp;&nbsp;&nbsp;"Compressing EVEX instrs when possible"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e733284e23180a07a59ede80b0baec1">COMP_EVEX_NAME</a>&nbsp;&nbsp;&nbsp;"x86-compress-evex"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;<a href="#a6e733284e23180a07a59ede80b0baec1">COMP_EVEX_NAME</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f21fe828d48a86f654b9f8bdeb740bc">GET_X86_COMPRESS_EVEX_TABLE</a></td>
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

### CompressEVEXImpl() {#a9d982c894cfe302bb2d90c1f5d4c1c37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CompressEVEXImpl (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; ST)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ac6417d5ffb5083fa98bcae081c2c75aaa125f1c180c3593a7ac6a2b350cc3d75a">llvm::X86::AC_EVEX_2_EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ac6417d5ffb5083fa98bcae081c2c75aaab5e973c821bc6607bd92a290f63a3cbd">llvm::X86::AC_EVEX_2_LEGACY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ac6417d5ffb5083fa98bcae081c2c75aaa8bd2d6952c01be113164446873c84c66">llvm::X86::AC_EVEX_2_VEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead5bbb0f8b7dfd268d7ca01219b5ec3aa">llvm::X86II::EncodingMask</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1224cf85d21a6023de72b90c2f225241">llvm::X86II::EVEX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea4a0b5ce031c6c73572f1006babe65b47">llvm::X86II::EVEX_B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eabe6298d9ba729db7fa5c2149de1b21ed">llvm::X86II::EVEX_K</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1b5f21917d273c19ffaa38e025d6b4af">llvm::X86II::EVEX_L2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eac83eba50896a8cee3fb15a329b94a21d">llvm::X86II::EVEX_NF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a279395a00a782f7e3d6141bc3328a249">llvm::X86::getFirstAddrOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af8606eab304dcbb9e0bb4b3597c49675">llvm::X86::getNFVariant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a7f5a82ba9421c1c89257282ca65b4c23">llvm::X86::getNonNDVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a3bab7f646d8804292fe0561f29f0c9c0">llvm::X86II::hasNewDataDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eaf345a1192eb67c66842be4eae52e9112">llvm::X86II::LEGACY</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a1fade9b6e8aab907e81b8efabc46c8d4">performCustomAdjustments</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc/#a46e0fcca2366f30d5e35b3d7dcb9c65f">llvm::MCInstrDesc::TSFlags</a>, <a href="#afdc3f396ced2d97e9feb5f89e6733457">usesExtendedRegister</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6702853ec24d45d810d71e321eb9e256">llvm::X86II::VEX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86compressevex-cpp-/compressevexpass/#ab3b2761d6e41f81db794148ce494e387">anonymous{X86CompressEVEX.cpp}::CompressEVEXPass::runOnMachineFunction</a>.</p>

</div>
</div>

### performCustomAdjustments() {#a1fade9b6e8aab907e81b8efabc46c8d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool performCustomAdjustments (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned NewOpc)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>.</p>

</div>
</div>

### usesExtendedRegister() {#afdc3f396ced2d97e9feb5f89e6733457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool usesExtendedRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#aed3a5dba6b8da462e693c4965ec7c911">llvm::X86II::isApxExtendedReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a301d6276fae739378e945ebbe0c8dd9b">llvm::X86II::isZMMReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### COMP\_EVEX\_DESC {#a14ab6af71c08308e021a231c619495e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMP_EVEX_DESC&nbsp;&nbsp;&nbsp;"Compressing EVEX instrs when possible"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86compressevex-cpp-/compressevexpass/#a001e5e5581b007c0002cd34365be936d">anonymous{X86CompressEVEX.cpp}::CompressEVEXPass::getPassName</a>.</p>

</div>
</div>

### COMP\_EVEX\_NAME {#a6e733284e23180a07a59ede80b0baec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define COMP_EVEX_NAME&nbsp;&nbsp;&nbsp;"x86-compress-evex"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;<a href="#a6e733284e23180a07a59ede80b0baec1">COMP_EVEX_NAME</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>

</div>
</div>

### GET\_X86\_COMPRESS\_EVEX\_TABLE {#a1f21fe828d48a86f654b9f8bdeb740bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_X86_COMPRESS_EVEX_TABLE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp">X86CompressEVEX.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
