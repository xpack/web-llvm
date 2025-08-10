---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AArch64MIPeepholeOpt.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-h">AArch64ExpandImm.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-h">AArch64InstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64addressingmodes-h">MCTargetDesc/AArch64AddressingModes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinedominators-h">llvm/CodeGen/MachineDominators.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineloopinfo-h">llvm/CodeGen/MachineLoopInfo.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64mipeepholeopt-cpp-">anonymous{AArch64MIPeepholeOpt.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt">AArch64MIPeepholeOpt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895c843f6492705523ec94b5dcc327cc">INITIALIZE_PASS</a> (AArch64MIPeepholeOpt, "aarch64-mi-peephole-opt", "AArch64 MI Peephole Optimization", false, false) template&lt; typename T &gt; static bool splitBitmaskImm(T Imm</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44820ac394a8f8fc10cdfa8e832fe1ce">if</a> (AArch64_AM::isLogicalImmediate(UImm, RegSize)) return false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6e5d6085bba2ab9a686dbf4e88a8b07">if</a> (Insn.size()==1) return false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34dcac5bf06a03d57cd29ba812c13ee">if</a> (!AArch64_AM::isLogicalImmediate(NewImm2, RegSize)) return false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb8ed73d70e625c6ab95a50c2ba8b546">splitAddSubImm</a> (T Imm, unsigned RegSize, T &amp;Imm0, T &amp;Imm1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4500019fb14b19bfa9ab473af4a50f5">is64bitDefwithZeroHigh64bit</a> (MachineInstr *MI, MachineRegisterInfo *MRI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned T &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889851703ca9d8e9e29dff0e51496f4c">Imm1Enc</a> = AArch64_AM::encodeLogicalImmediate(<a href="#a715faf60f43d6e87239e1e54f2d40c69">NewImm1</a>, <a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a>)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned T T &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a16986e8de624f2399df45e137ecb16">Imm2Enc</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/aarch64-imm/imminsnmodel">AArch64_IMM::ImmInsnModel</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d5dc120196819fbfbc257cba09b2aa">Insn</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92e3a8315d26f5dd435235432c85f6e">LowestBitSet</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>(UImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a665a4309d89d2f4965f797bb3990f9a5">HighestBitSet</a> = Log2_64(UImm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a715faf60f43d6e87239e1e54f2d40c69">NewImm1</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">T</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953c552820189b36cbd66d77a1ea639a">NewImm2</a> = UImm | ~<a href="#a715faf60f43d6e87239e1e54f2d40c69">NewImm1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">return</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930920b2bc42824a5c03be681830f4b2">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-mi-peephole-opt"</td>
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

### if() {#a44820ac394a8f8fc10cdfa8e832fe1ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (AArch64_AM::isLogicalImmediate(UImm, <a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a>))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a262431cccd14e6063eacc180130a5882">llvm::AArch64_AM::isLogicalImmediate</a> and <a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a>.</p>

</div>
</div>

### if() {#aa6e5d6085bba2ab9a686dbf4e88a8b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (Insn. size=()==1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Reference <a href="#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>.</p>

</div>
</div>

### if() {#ab34dcac5bf06a03d57cd29ba812c13ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">if (! AArch64_AM::isLogicalImmediate=NewImm2, RegSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>References <a href="#a889851703ca9d8e9e29dff0e51496f4c">Imm1Enc</a>, <a href="#a7a16986e8de624f2399df45e137ecb16">Imm2Enc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a262431cccd14e6063eacc180130a5882">llvm::AArch64_AM::isLogicalImmediate</a>, <a href="#a715faf60f43d6e87239e1e54f2d40c69">NewImm1</a>, <a href="#a953c552820189b36cbd66d77a1ea639a">NewImm2</a> and <a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a895c843f6492705523ec94b5dcc327cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (AArch64MIPeepholeOpt, "aarch64-mi-peephole-opt", "AArch64 <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> Peephole Optimization", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### is64bitDefwithZeroHigh64bit() {#ab4500019fb14b19bfa9ab473af4a50f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool is64bitDefwithZeroHigh64bit (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> * MRI)</td>
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



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a3ae1d5f3372a2112a1cea9b8c8e21736">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitFMOVDr</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#ad457d12e54f0a38894c84aa6901838b5">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitINSvi64lane</a>.</p>

</div>
</div>

### splitAddSubImm() {#abb8ed73d70e625c6ab95a50c2ba8b546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool splitAddSubImm (T Imm, unsigned RegSize, T &amp; Imm0, T &amp; Imm1)</td>
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



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="#a96d5dc120196819fbfbc257cba09b2aa">Insn</a>, <a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a08d97216cdc088a0055e5cd597814ddb">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSSUBS</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a9cdd873b7d4271334f198670b51934f4">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSUB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### HighestBitSet {#a665a4309d89d2f4965f797bb3990f9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned HighestBitSet = Log2_64(UImm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>

</div>
</div>

### Imm1Enc {#a889851703ca9d8e9e29dff0e51496f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Imm1Enc = AArch64_AM::encodeLogicalImmediate(<a href="#a715faf60f43d6e87239e1e54f2d40c69">NewImm1</a>, <a href="#a9c374320ed4e895f9afa199987182bd2">RegSize</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab34dcac5bf06a03d57cd29ba812c13ee">if</a>.</p>

</div>
</div>

### Imm2Enc {#a7a16986e8de624f2399df45e137ecb16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Imm2Enc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">{
  T UImm = static_cast&lt;T&gt;(Imm)
</div>
</dd>
</dl>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab34dcac5bf06a03d57cd29ba812c13ee">if</a>.</p>

</div>
</div>

### Insn {#a96d5dc120196819fbfbc257cba09b2aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;AArch64_IMM::ImmInsnModel, 4&gt; Insn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac3376db6d9d68aaa00b187b27fe7e37d">checkDecodedInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aa9145488452fa21d947ebb7f908f344b">collectPreserveStaticOffsetCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ad9ad399db3974f5eaa5aef42b788b973">Decode2OpInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ad82f20fea871b64a234b4e8829be924d">Decode2OpInstructionFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a950119e64de8aa5eb4bfbc37c275e8e1">Decode2RImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ae69c1ddc534b34b5028e90da0b3ad893">Decode2RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ab147b919c73ac4d62df30f270fb3604e">Decode2RSrcDstInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a043c116a6ba20ff396abb71a2de5e8b9">Decode2RUSBitpInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a6efa6cced81498c9b0dd1c674f2b715b">Decode2RUSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a81941cb599a91e8d30c8b122a7487e6a">Decode3OpInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a869e2b76735fa0bbd12f1ac4d87d045c">Decode3RImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#afe549cdb8b9fbe42b5b737056dd0d72f">Decode3RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a01159155e0e1288fdee10e8077d347e4">DecodeAddrMode2IdxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a748fded8b9c14e77783f32aa13b93af7">DecodeAddrMode3Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#affbdff2d7ee69783b269fca2b967b7a8">decodeAField</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a8f6b082ac25a5bc7c68fa858b9ad7634">DecodeANDI16Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2d3a2f957bed112cb510b5d278872555">DecodeArmMOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a6c70fd25f059a226c407ddfeb4fc3ae7">decodeBField</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a063313765e2dd0018f7e55bf4cb00ba4">decodeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a36413fd3a08347a6defae0004efa31ba">DecodeBranchImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad2dc21f24745f289fc5e70691052ac9e">DecodeCacheeOp_CacheOpR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4b99d1243931be14e14f7899b31458d4">DecodeCacheOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a179adc6990bb000f20132a4f4388ef12">DecodeCacheOpMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#a726ea22689798949a755d3782f125f76">DecodeCCRCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a04341f61408b84cf6d7b2b0a0485e437">DecodeCCRU6Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a5bfa2ec4204200e2afb6bedb6469e1cb">decodeCField</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#aa5419c3888e7adeccf45d102b0dd09d1">decodeCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7b3ca5b536ce1c58a39b853ea79de51b">DecodeCopMemInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9cf0adb29491a93fac8fe34fd2a70356">DecodeCPSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a30c59aff7e6ea364c4caadcabdceeb82">DecodeCRC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a7644a0e2bcc52e1863d42f64b7690b0d">decodeCSSPushPopchk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5f85af7cd5d35e2daba62960dbaa43d4">DecodeDEXT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a369950ccd05ebc3ecb3fbf4a48b0e835">DecodeDINS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4144ff726054b8ab8750ac9b60da1979">DecodeDoubleRegLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a067843ccf524c115a5ce33144d3aace8">DecodeDoubleRegStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#a9720d794b7199e7641e9934ba9c4ab7c">DecodeDstAddrMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#afcde096b672e6803bbd1dc93eecc6f65">decodeFBRk</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#aae3430fd644bb621029ad778235f3321">decodeFFMULRdRr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a4b551520c4790afaae3b181553ba8d0b">decodeFIOARr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a976dffced44495ff439f2fc6a1f18037">decodeFIOBIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a975b91cc45a879ff0dbfb929f08e5a1b">decodeFIORdA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a8c0fbe6fc681cad36a63d5e255b058ed">DecodeFIXMEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a1ac00c1502d95cb55fc0bce5eeade208">decodeFLPMX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4a95f69f6c5c027fc46fa94fcd465045">DecodeFMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5506baa3dada53698432a211bb3b4289">DecodeFMem2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a6d0d0fbc04194d17d3039dfd16666715">DecodeFMem3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a01c88b37f10b149a379442567798c604">DecodeFMemCop2MMR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#aeaf09a414c497b64bc8882d42c77f7d0">DecodeFMemCop2R6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#acfee40040ef185edd60491ec6e58687c">DecodeFMemMMR2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#ad6446846a7c3fa3ae63776aef7ed03df">DecodeFMOVLaneInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#ad8d3b2647f106313e78dcea2d36d017d">decodeFMOVWRdRr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a32943db09b6a9ae176fac6269b174806">decodeFMUL2RdRr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a04cfe715378434d5257a31c6011fe8f5">decodeFRd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a426cc36e610cb3fefd547ab4e42b8e62">decodeFWRdK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ae96b7f8b4b8e35d28617a90604289b0b">DecodeHINTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af2e78b5e65ffb6775845fc0212d3145b">DecodeInsSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a81a160da998ad8c220a42b326635c347">DecodeIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ae70463d5ebd44edcb0f55e8f71ea13cd">DecodeJumpTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#adbc74232b42622af980395b81c707b63">DecodeJumpTargetMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a12f0fe80f72fa867a56f7656bc69ba82">DecodeJumpTargetXMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a57891cd6e61d7d49104b0b2ea382d721">DecodeL2OpInstructionFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a82aae0bef02321af595fb8748f76e79e">DecodeL2RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a0e464d2190a7b98aca0f9fc5d0d2119c">DecodeL2RUSBitpInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a34fffc378f5dce35182c9d7d6d90dc91">DecodeL2RUSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a451f046bc29b34325041d69368e78bd4">DecodeL3RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a752e5e3f1c0b9e68bfee7335e1f12bcc">DecodeL3RSrcDstInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a3ba67869d65eed374bba67510c7d462c">DecodeL4RSrcDstInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a3059bcf478998c347b07a2ad802c8459">DecodeL4RSrcDstSrcDstInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a7e3780955dbf7869658844507f924f73">DecodeL5RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#aaec91c96968a65d0fa1bf2165345258d">DecodeL5RInstructionFail</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#abbce426404d7d806f822f60b90dfa0fd">DecodeL6RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afbc53e43e60687c280c643165c8c8a16">DecodeLazyLoadStoreMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#aa7956d4781c08702515a296790075c9d">DecodeLdLImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a1de0eac0bd3c65f8050ee57e0a004867">DecodeLdRLImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ade3de8655e8cd7260d807f9cea0701b8">DecodeLDRPreImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a04f793a8e90b0d329fdea0bb8c1f2356">DecodeLDRPreReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5226be2f481d1b712b374a6106eb05e7">DecodeLoadByte15</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a2cb3aca8e9408d30eaf90bd4c70e65e4">decodeLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afecebd0151d705a1f451129515690010">DecodeLOLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a14eb0791906feaeaca5245f3a08b2536">DecodeLR2RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af6be4e043e94b84a2f41ca62f43e2c33">DecodeMem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0846cbb46ed7dfb0fe8963f57e4e450c">DecodeMemEVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#afc5d4d8f5a682f4c0ea86db0681099f0">DecodeMemMMGPImm7Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a5cdc282caa88d2f28ce4792ad53d4471">DecodeMemMMImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ad2f3f439d59b03ed49013e7aeaafd701">DecodeMemMMImm16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a97875810a5d927cedd5b85ab368caf67">DecodeMemMMImm4</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a2a99cbe29aa769217b2e94ed6248575e">DecodeMemMMImm9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a7bd5fcbe5963096279a236cbdf87e675">DecodeMemMMReglistImm4Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ac3bab0bdce9c5d10efa38d46bd79271c">DecodeMemMMSPImm5Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aee22f63177a59f1c073fc689b38933ae">DecodeMemMultipleWritebackInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a337776342a5c26b5f50cb4186114622b">decodeMemoryOpValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#abf5533403c67de41a3b98d96699419ee">decodeMemri</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#af48dd6610db11d5275ece9154300e514">DecodeMEMrs9</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a347760ad409026bf174cb84186f2db33">DecodeMoveHRegInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a2fc2957a7a0cc43e2e48320b4675b4fb">DecodeMovePOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a38cb0684cd1dac98218884dbd1ffbb85">DecodeMSA128Mem</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaa973fa80051d521ca126e6baec9b849">DecodeMveAddrModeQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aba042b54f8c582939b1efa62e08000b3">DecodeMveAddrModeRQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa6165f97e90eaea7675b635e2d2a1a3a">DecodeMVEModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ace68fb9d35b1e3f7c97175ebeb16e386">DecodeMVEOverlappingLongShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aec419b455f0b73caa44637f09817ec4f">DecodeMVEVADCInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a111ed526e6e5818e4bd6f7c459c883ab">DecodeMVEVCMP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac31edd9f4eb883611f651f89005c8878">DecodeMveVCTP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab201350cfc0d9d9353ffc3c7b4d99b5c">DecodeMVEVCVTt1fp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a1270d23ac4d95c35151585a99d022028">DecodeMVEVMOVDRegtoQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ab75960dda5858220e6442740cd47c020">DecodeMVEVMOVQtoDReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0dd59a3d5dbf53a9ccf82fa0463a4f6d">DecodeMVEVPNOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a03d54559851ae68e67660bdd39fc0f83">DecodeNEONComplexLane64Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a968efe31b652445ecd031c2d15a1ae31">DecodePostIdxReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a3d785e380546672d88587a25478a3dc4">DecodePrefeOpMM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a46ace96c930c483858d57c90bbeaa257">DecodeQADDInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a80160a624b9ca89664e3edb9a216e158">DecodeR2RInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0e63c91ecc76f4cc56a896dd3ab65f38">DecodeRegListOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#abf0a19aed27d5d513d9891ae3d48bc31">DecodeRegListOperand16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a01d733f628f161dbaefbfa5d5fd1cf34">decodeRegReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aedf86c5895d19485c6219652fdf5bd3d">DecodeRFEInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a4c912311e2594387fe7d03e6346a0d1a">decodeRiMemoryValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a2530547533fd87c8f94a6a72164cf4de">decodeRrMemoryValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ab914ed964aaa2a6a0563942879fc114a">DecodeRUSBitpInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a10ccb4290c3d7bd10eec473c054c3612">DecodeRUSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a339eaddfb786c80be0cd5dce7c181ed3">DecodeRUSSrcDstBitpInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a4fb3fc8c5d55a1d56d78a9df5741397b">decodeRVCInstrRdRs1ImmZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a19d0efeb7b5278d64f33d0423d2bd8ac">decodeRVCInstrRdRs1Rs2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#adfdd862b7dee084ab03c01966116902b">decodeRVCInstrRdRs1UImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#aac0bda24da3232c423757577080630c8">decodeRVCInstrRdRs2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a90702c263ae4dbf20b0f59ef58f13f7c">decodeRVCInstrRdSImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ee0d80338b8a6c928f2322e35a21c37">DecodeSETPANInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#aad4e6692a45bcddab57965902ebb6c3f">decodeShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a6bb5a4fe2dd2871aa0b0407277291ce9">DecodeSimm18Lsl3</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a026fc24df0672a9950dcbf77264e7e05">DecodeSimm19Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a249776a60fa6ebe72af4a50fdb2adfd6">DecodeSimm23Lsl2</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a53857c68e589210e0c059cb970577183">DecodeSimm9SP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a75cd3f70d0beaa0d481f60be56a927cc">DecodeSMLAInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a746079c286d5e7dfd559520006cdbc82">DecodeSOPwithRS12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a2197fd22b3d4ec0302f9cc79d12a3402">DecodeSOPwithRU6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab357e7edc71c6ac759f843c8a4d2e525">DecodeSpecial3LlSc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a3c110cd89ae07dc4a4a8f88fd316938a">decodeSplsValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#aa6a2ae26f914b45d5d1e18c54692e566">DecodeSrcAddrModeI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#a857781b83f8088fb6abc1672c5600ec8">DecodeSrcAddrModeII</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#a034a2637c66968c16bcf13d44068b91f">DecodeSRCRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#ad49072913256760cce9a52ad08e123a6">DecodeStLImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aca8d5712120853edda117fb57ac24c00">DecodeSTRPreImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a496c8b0fe7b5fda345cc839544357d40">DecodeSTRPreReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a764505cabfd01c2f66766fa3549edbac">DecodeSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ae431d705509fa5518935c0316e0f7f75">DecodeSyncI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a4d85eac7627a2960509a89db115ee3ea">DecodeSyncI_MM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#ab67a4db8c7b5eee3b7e1a2285a9b04ba">DecodeSynciR6</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5686943937ea2fcb33898d72abca31ef">DecodeT2AddSubSPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#af29ab03d6050c790ddb78a16ec44a9c8">DecodeT2Adr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aef9eb2cb70ef337f38412e1abbf0dec1">DecodeT2BInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7e582cac45ed6985921e4bb6a2f7d648">DecodeT2CPSInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aded3e7ff6d138e828bcbcce6cb174baf">DecodeT2HintSpaceInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9ac46a3cd7dcc8838c2173bf507a330d">DecodeT2LDRDPreInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa0db3bd9104dd7f086c6f8686f59c288">DecodeT2LdStPre</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a57b019630c1fd92a4bf745e6639f344a">DecodeT2LoadImm12</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa5cc177b319e4695ef7c2b627ed4a5e6">DecodeT2LoadImm8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a18ec82d05c3fecd8d313d76aa6cf4d88">DecodeT2LoadLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aaab47c414bc9052d5ae109a30036ae38">DecodeT2LoadShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a08bf371630cff66c49e3aaebc6b7337d">DecodeT2LoadT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a3d6b4d56448a550e780bcc286defca12">DecodeT2MOVTWInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a53eeac5ee65d08a3ba41f4bdb8f2187e">DecodeT2ShifterImmOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a862021f0473d4d7455f3edfea8465b7d">DecodeT2STRDPreInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ade174bb0481f851b34f77b9f83c5b7ae">DecodeTBLInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a2c2187f74d4f13ec46f8bd522ab7f5e4">DecodeThumb2BCCInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9d49e57d960810a6cdebef656a7d12c1">DecodeThumbAddSpecialReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9239d3121cc71b12f5345bd426bdd9ac">DecodeThumbAddSPImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4ff9913a6a8ee09237b7bdb7350f8758">DecodeThumbAddSPReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9bcf5304e1403680817795f4f0cfbe3a">DecodeThumbCPS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a23720a1f4582fe48cb949b1189f3d058">DecodeThumbTableBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a406420d233c9c21f4c1bfbc6328c7651">DecodeTSBInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#adc97046c80e5338d47c2e57439d3d58d">DecodeTSTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a78802c522ed764cedc1bafcf628dd154">DecodeVCVTD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a9e5902642b306bad7e557cc0030a8c3b">DecodeVCVTQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a4bc58a6a4cc485df54316ee63961494a">DecodeVLD1DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a88cfc4461fad680d4d3b2dca75c06462">DecodeVLD1LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#adbfb7c834c41c75925284ebcb3e30a43">DecodeVLD2DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a55963f98bd8421645c77a3bc2497015d">DecodeVLD2LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a7bce2d579f601f86a9e4746623988063">DecodeVLD3DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a989cc7ee36e295c4132740950cd1aec8">DecodeVLD3LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a53b3d214dc2e26fcfb82d711dd7e897f">DecodeVLD4DupInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a241bba0734ea7a40a6fb2b7cfc63f72e">DecodeVLD4LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa46c26cc972273e7463a3ebe3a9cedad">DecodeVLDInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#accb04371e1109a8feda7773b8533ffbe">DecodeVLDST1Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a709cc909ac9c1da401fd511d827be2bf">DecodeVLDST2Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a6c6301248fde1135f3a83deecc0a7ca8">DecodeVLDST3Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa091c85ab9493d54433d6c4d0f4fa99c">DecodeVLDST4Instruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a41d6edfa220d2050c7c245dd1e5e5fec">DecodeVMOVModImmInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a67d16298e447dd109816c49a4d6b2de6">DecodeVMOVRRS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#afa9ccba50c08dbd23c30037e0a0ee6f8">DecodeVMOVSRR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aea8ff3695bbef57d56a2d23873b029bf">DecodeVSCCLRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a0d6877e515e068fc4847049790f9db94">DecodeVSHLMaxInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a585fe45145ba2dfdfbddf6544fbcc853">DecodeVST1LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#acc2c3a559d83ea0fc94b5cd90fa6b774">DecodeVST2LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a5bc2379dda1ba55eae95c132f3cc5e99">DecodeVST3LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#ac5d71fed959a923e986adb309f260ea9">DecodeVST4LN</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#a83aef7e6f90ca5e44f3927132a133315">DecodeVSTInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#a658e7d113d0172f3dad093f32851616c">decodeXTHeadMemPair</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-imm/#a77a4e6615fbc6c2bbcf179370dbd0fa9">llvm::AArch64_IMM::expandMOVImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a2edf9e8f09bfb0cc4949aa1813872322">expandMOVImmSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a35c9927607481d33c2093c2b7d643e80">fillCommonArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a61b5cb822ee8e25eee3418a520337962">findCommonDominator</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64mctargetdesc-cpp-/aarch64mcinstranalysis/#ab74d7f466279e42ef6ac5ba405ef4301">anonymous{AArch64MCTargetDesc.cpp}::AArch64MCInstrAnalysis::findPltEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ab15c69cfc260f1de61bb644d88b1ed85">foldSelectToPhiImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrdisassembler-cpp-/avrdisassembler/#ab1ae8549e0858c6f3efb2ed514cdf560">anonymous{AVRDisassembler.cpp}::AVRDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfdisassembler-cpp-/bpfdisassembler/#a5046a0024e7712f11848e29914c387b6">anonymous{BPFDisassembler.cpp}::BPFDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskydisassembler-cpp-/cskydisassembler/#ab02ac21009a84db6e0a786c08e2be1b5">anonymous{CSKYDisassembler.cpp}::CSKYDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdisassembler-cpp-/loongarchdisassembler/#a38b30661f2481e385870d52d8cc9e996">anonymous{LoongArchDisassembler.cpp}::LoongArchDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsdisassembler-cpp-/mipsdisassembler/#a13382001a79658a93283128f5c32a051">anonymous{MipsDisassembler.cpp}::MipsDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430disassembler-cpp-/msp430disassembler/#a55019fcf219b7cac44ca62e49a0eeb6a">anonymous{MSP430Disassembler.cpp}::MSP430Disassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcdisassembler-cpp-/sparcdisassembler/#a845997f39706b9123a8c3f9d6b7bf3f0">anonymous{SparcDisassembler.cpp}::SparcDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-vedisassembler-cpp-/vedisassembler/#a73f28e529d7fea5bf343716c3f6c12ba">anonymous{VEDisassembler.cpp}::VEDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86disassembler-cpp-/x86genericdisassembler/#a5872d463242e5872d4df00b5862e403f">anonymous{X86Disassembler.cpp}::X86GenericDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-xtensadisassembler-cpp-/xtensadisassembler/#a04a91a09d50c64eae4efa4562ec4a475">anonymous{XtensaDisassembler.cpp}::XtensaDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64disassembler/#aeb2497953080ddc86f9e05b674454ac6">llvm::AArch64Disassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaidisassembler/#ab76206f183c98836269293f7e597b8f7">llvm::LanaiDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/structs/m68kdisassembler/#a148939039bc8201973e8931087aa62a6">M68kDisassembler::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#aca56c12eb63eea9e71e826a1e888b51d">llvm::AArch64TTIImpl::getIntImmCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsbranchexpansion-cpp/#afa225aa7b0b7c2076978f4991a00c7b5">getNextMachineInstrInBB</a>, <a href="#aa6e5d6085bba2ab9a686dbf4e88a8b07">if</a>, <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking/#a6680bd71c9d15033f99c787b50d09e47">llvm::ImplicitControlFlowTracking::isDominatedByICFIFromSameBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/memorywritetracking/#a43d110285c732a61a66f2c91a6f02d2f">llvm::MemoryWriteTracking::isDominatedByMemoryWriteFromSameBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a0b5597ce1a7049500d0b30bef14951ca">llvm::AArch64TargetLowering::isFPImmLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa36af57c5a44173f32eb7b4c9011c298">llvm::isGuardAsWidenableBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#af8e97755935ce2a3c03a0ba055b310c2">llvm::AArch64TargetLowering::isMulAddWithConstProfitable</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#adeff4bfc41e787e8074a500fe3f2fbb7">llvm::InstructionPrecedenceTracking::isPreceededBySpecialInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0eee77cb45ab15bd00718f8801a3fc53">llvm::ARMTTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a2e5edb7304bd217445cdd2bff95ab43c">llvm::RISCVTTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/implicitcontrolflowtracking/#ae08e452a5b7166504b29a1d9140e4525">llvm::ImplicitControlFlowTracking::isSpecialInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#ad557cd72cd34de96e4d0bc67f4037643">llvm::InstructionPrecedenceTracking::isSpecialInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/memorywritetracking/#ad4c4277cbea86cbea61789fa5b98d1ba">llvm::MemoryWriteTracking::isSpecialInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp/#a06f1432892d38967fd37f87b142994d5">isSupportedGuardInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a006d92e5eae5fd3ca76b72ec1b749a1b">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::mergeUpdateInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a45e407f6e7148030f31c1063d12d25b0">PostOperandDecodeAdjust</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#ae833f3168bbfb866c7e699bcc31fa19a">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a891641445e1af3e482f70a7264fba239">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#a9cf94f76dec1de7e52ae168a3f24d86b">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a197258c284317a10774b00294361183b">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a9da1c2a7c067001d8f7a38330911f457">readInstruction16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a328747ad97067de92be77a78b8f9507d">readInstruction24</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a2cc677eee55aee4a2a187254920d121c">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a9d2ff5b7963ea79edc3889c72d7c39f5">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#ac019218333036d85003d3db715dfcab7">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#a9d2ff5b7963ea79edc3889c72d7c39f5">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a0f7c0a1c6dcff81f4f35cebe317bde15">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#aa30249bb0a7b58400839efb59e26eaff">readInstruction32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a06df81cdff05ab7e363c6200e08a4521">readInstruction48</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a682f94cca74aeb23b1ab9c3b21380524">readInstruction64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a3fcc2328b16aab5f5620750b7e9b4c41">readInstruction64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#a3fcc2328b16aab5f5620750b7e9b4c41">readInstruction64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#abff89c097ca3eb3d820b684175b4008f">reconstructCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#aceb0dbb192df1147bd5191db4c960ec1">removeGEPBuiltinsInFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a373ff831d4d84fda2a1a0f32e8cfb09e">reportNonStaticGEPChain</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldmachoarm/#a42b1bc914cf22878c36dda7a8a31447e">llvm::RuntimeDyldMachOARM::resolveRelocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a732f3ff01555ec522134bf060270c1ae">rewriteAccessChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a4a1ded9f22bc97a6e916c9836ea967b8">rewriteUses</a>, <a href="#abb8ed73d70e625c6ab95a50c2ba8b546">splitAddSubImm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64postlegalizerlowering-cpp-/#a681a012ac18b27513b6715881d002520">anonymous{AArch64PostLegalizerLowering.cpp}::tryAdjustICmpImmAndPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#aa20f3eb24c28efa9c93053a733a172c1">tryAndOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#ab2f723b31c9dbe46610248a047805046">tryEorOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#ae492dde0ae62ef0c16a80f8b648bae19">tryOrrOfLogicalImmediates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a7000ac817f63a64697020f0538311927">trySequenceOfOnes</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandimm-cpp/#a6efd5b30fe34a042d2937ba63a73ad07">tryToreplicateChunks</a>.</p>

</div>
</div>

### LowestBitSet {#ac92e3a8315d26f5dd435235432c85f6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LowestBitSet = <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>(UImm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>

</div>
</div>

### NewImm1 {#a715faf60f43d6e87239e1e54f2d40c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T NewImm1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= (static_cast&lt;T&gt;(2) &lt;&lt; <a href="#a665a4309d89d2f4965f797bb3990f9a5">HighestBitSet</a>) -
              (static_cast&lt;T&gt;(1) &lt;&lt; <a href="#ac92e3a8315d26f5dd435235432c85f6e">LowestBitSet</a>)
</div>
</dd>
</dl>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab34dcac5bf06a03d57cd29ba812c13ee">if</a>.</p>

</div>
</div>

### NewImm2 {#a953c552820189b36cbd66d77a1ea639a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T NewImm2 = UImm | ~<a href="#a715faf60f43d6e87239e1e54f2d40c69">NewImm1</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Referenced by <a href="#ab34dcac5bf06a03d57cd29ba812c13ee">if</a>.</p>

</div>
</div>

### RegSize {#a9c374320ed4e895f9afa199987182bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned RegSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a57484713254f31f8412d08ff85259761">llvm::DwarfExpression::addMachineReg</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a8337bafd341ca7fa36509bf0ad142c57">llvm::DwarfExpression::addMachineRegExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzxplinkframelowering/#af8195925dae80a73b2c6101290b5962b">llvm::SystemZXPLINKFrameLowering::assignCalleeSavedSpillSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a05e32f779d033fe0757134346ba52aa2">createPSADBW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abdfa1a0a4242f9dfe9591c6be92c0178">createVPDPBUSD</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a058c4d3a1147ae3ec1098c3031fe32cb">llvm::CSKYFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a0b91e092434338369b2e1995b87f0c5b">determineVPlanVF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsframelowering/#a7c45383cd53ee8ccfeceafc1daed18d3">llvm::MipsFrameLowering::estimateStackSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a4e648e81989bc63b0dac82e5638c31d6">llvm::TargetRegisterInfo::getRegSizeInBits</a>, <a href="#ab34dcac5bf06a03d57cd29ba812c13ee">if</a>, <a href="#a44820ac394a8f8fc10cdfa8e832fe1ce">if</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a812ebabddd1ad2d8f8bbc6194346e2ed">isLoadStoreSizeLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#abed37e9eeb67324751569d54ac13c0ef">isNonFoldablePartialRegisterLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a3a0c76714485f4713fed0661f961b09a">llvm::MipsCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5d600f23e7d301bfcf60b292eaba31ef">llvm::CombinerHelper::matchCombineLoadWithAndMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64-am/#a2cd3e23b97b495a98c0b723ab18e4d96">llvm::AArch64_AM::processLogicalImmediate</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#ad60d6849c72ab45eeefc4951c3dcc215">sizeOfSPAdjustment</a>, <a href="#abb8ed73d70e625c6ab95a50c2ba8b546">splitAddSubImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a92e31a04c0a1b5d17db90c99fa48f6aa">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::splitTwoPartImm</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a08d97216cdc088a0055e5cd597814ddb">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSSUBS</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a9cdd873b7d4271334f198670b51934f4">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitADDSUB</a> and <a href="/web-llvm/docs/api/structs/anonymous-aarch64mipeepholeopt-cpp-/aarch64mipeepholeopt/#a1aeb260a435d4ca4ca00e380df4546c6">anonymous{AArch64MIPeepholeOpt.cpp}::AArch64MIPeepholeOpt::visitAND</a>.</p>

</div>
</div>

### true {#a930920b2bc42824a5c03be681830f4b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">return true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-mi-peephole-opt"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64mipeepholeopt-cpp">AArch64MIPeepholeOpt.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
