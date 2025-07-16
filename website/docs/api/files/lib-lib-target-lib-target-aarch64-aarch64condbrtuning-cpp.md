---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/aarch64/aarch64condbrtuning-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `AArch64CondBrTuning.cpp` File Reference

<p>This file contains a pass that transforms CBZ/CBNZ/TBZ/TBNZ instructions into a conditional branch (B.cond), when the NZCV flags can be set for "free". <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64-h">AArch64.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64subtarget-h">AArch64Subtarget.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-aarch64condbrtuning-cpp-">anonymous{AArch64CondBrTuning.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-aarch64condbrtuning-cpp-/aarch64condbrtuning">AArch64CondBrTuning</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34e1a5258c045fdf41f4ce2580387a00">INITIALIZE_PASS</a> (AArch64CondBrTuning, "aarch64-cond-br-tuning", AARCH64_CONDBR_TUNING_NAME, false, false) void AArch64CondBrTuning</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"aarch64-cond-br-tuning"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e1893093f83da1705c725fb3b5cbccd">AARCH64_CONDBR_TUNING_NAME</a>&nbsp;&nbsp;&nbsp;"AArch64 Conditional Branch Tuning"</td>
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

<p>This file contains a pass that transforms CBZ/CBNZ/TBZ/TBNZ instructions into a conditional branch (B.cond), when the NZCV flags can be set for "free".</p>


<p>This is preferred on targets that have more flexibility when scheduling B.cond instructions as compared to CBZ/CBNZ/TBZ/TBNZ (assuming all other variables are equal). This can also reduce register pressure.</p>


<p>A few examples:</p>


<p>1) add w8, w0, w1 -&gt; cmn w0, w1 ; CMN is an alias of ADDS. cbz w8, .LBB_2 -&gt; b.eq .LBB0_2</p>


<p>2) add w8, w0, w1 -&gt; adds w8, w0, w1 ; w8 has multiple uses. cbz w8, .LBB1_2 -&gt; b.eq .LBB1_2</p>


<p>3) sub w8, w0, w1 -&gt; subs w8, w0, w1 ; w8 has multiple uses. tbz w8, #31, .LBB6_2 -&gt; b.pl .LBB6_2</p>


<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS() {#a34e1a5258c045fdf41f4ce2580387a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (AArch64CondBrTuning, "aarch64-cond-br-tuning", <a href="#a6e1893093f83da1705c725fb3b5cbccd">AARCH64_CONDBR_TUNING_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64condbrtuning-cpp">AArch64CondBrTuning.cpp</a>.</p>


<p>References <a href="#a6e1893093f83da1705c725fb3b5cbccd">AARCH64_CONDBR_TUNING_NAME</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AARCH64\_CONDBR\_TUNING\_NAME {#a6e1893093f83da1705c725fb3b5cbccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AARCH64_CONDBR_TUNING_NAME&nbsp;&nbsp;&nbsp;"AArch64 Conditional Branch Tuning"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64condbrtuning-cpp">AArch64CondBrTuning.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64condbrtuning-cpp-/aarch64condbrtuning/#a9360521aaef71076ba1dc13624808215">anonymous{AArch64CondBrTuning.cpp}::AArch64CondBrTuning::getPassName</a> and <a href="#a34e1a5258c045fdf41f4ce2580387a00">INITIALIZE_PASS</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"aarch64-cond-br-tuning"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64condbrtuning-cpp">AArch64CondBrTuning.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
