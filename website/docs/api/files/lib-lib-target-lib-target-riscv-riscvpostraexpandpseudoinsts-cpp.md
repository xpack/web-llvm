---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/riscv/riscvpostraexpandpseudoinsts-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVPostRAExpandPseudoInsts.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscv-h">RISCV.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-h">RISCVInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-riscvpostraexpandpseudoinsts-cpp-">anonymous{RISCVPostRAExpandPseudoInsts.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-riscvpostraexpandpseudoinsts-cpp-/riscvpostraexpandpseudo">RISCVPostRAExpandPseudo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28c60a4327c56a9e40cc5258dcd1d21">INITIALIZE_PASS</a> (RISCVPostRAExpandPseudo, "riscv-post-ra-expand-pseudo", RISCV_POST_RA_EXPAND_PSEUDO_NAME, false, false) namespace llvm</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a396677434cbcaaa3996ff3eddca98198">RISCV_POST_RA_EXPAND_PSEUDO_NAME</a>&nbsp;&nbsp;&nbsp;  "RISC-V post-regalloc <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
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

### INITIALIZE\_PASS() {#af28c60a4327c56a9e40cc5258dcd1d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (RISCVPostRAExpandPseudo, "riscv-post-<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64stacktaggingprera-cpp/#a3d9786aba23105131dc05d9f8bfcac7a">ra</a>-<a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>-pseudo", <a href="#a396677434cbcaaa3996ff3eddca98198">RISCV_POST_RA_EXPAND_PSEUDO_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvpostraexpandpseudoinsts-cpp">RISCVPostRAExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2c8bc915c574473cf5c362d32e7ff9f7">llvm::createRISCVPostRAExpandPseudoPass</a>, <a href="#a396677434cbcaaa3996ff3eddca98198">RISCV_POST_RA_EXPAND_PSEUDO_NAME</a> and <a href="/web-llvm/docs/api/classes/anonymous-riscvpostraexpandpseudoinsts-cpp-/riscvpostraexpandpseudo/#a807e69580b41143b110518faef41d9c7">anonymous{RISCVPostRAExpandPseudoInsts.cpp}::RISCVPostRAExpandPseudo::RISCVPostRAExpandPseudo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### RISCV\_POST\_RA\_EXPAND\_PSEUDO\_NAME {#a396677434cbcaaa3996ff3eddca98198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RISCV_POST_RA_EXPAND_PSEUDO_NAME&nbsp;&nbsp;&nbsp;  "RISC-V post-regalloc <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvpostraexpandpseudoinsts-cpp">RISCVPostRAExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvpostraexpandpseudoinsts-cpp-/riscvpostraexpandpseudo/#a9cf10b865b643d29e520ee1dc32ac2ea">anonymous{RISCVPostRAExpandPseudoInsts.cpp}::RISCVPostRAExpandPseudo::getPassName</a> and <a href="#af28c60a4327c56a9e40cc5258dcd1d21">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
