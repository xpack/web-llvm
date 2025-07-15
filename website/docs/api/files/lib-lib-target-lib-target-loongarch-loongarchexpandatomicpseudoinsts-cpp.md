---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/loongarch/loongarchexpandatomicpseudoinsts-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LoongArchExpandAtomicPseudoInsts.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarch-h">LoongArch.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchinstrinfo-h">LoongArchInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchtargetmachine-h">LoongArchTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/livephysregs-h">llvm/CodeGen/LivePhysRegs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-loongarchexpandatomicpseudoinsts-cpp-">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandatomicpseudoinsts-cpp-/loongarchexpandatomicpseudo">LoongArchExpandAtomicPseudo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92d56fda40328eb8068ec5b0591c1ef">INITIALIZE_PASS</a> (LoongArchExpandAtomicPseudo, "loongarch-expand-atomic-pseudo", LoongArch_EXPAND_ATOMIC_PSEUDO_NAME, false, false) namespace llvm</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac00ca0d43e48b3ee7160cf6729ec3556">LoongArch_EXPAND_ATOMIC_PSEUDO_NAME</a>&nbsp;&nbsp;&nbsp;  "LoongArch atomic <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
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

### INITIALIZE\_PASS() {#aa92d56fda40328eb8068ec5b0591c1ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (LoongArchExpandAtomicPseudo, "loongarch-<a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>-atomic-pseudo", <a href="#ac00ca0d43e48b3ee7160cf6729ec3556">LoongArch_EXPAND_ATOMIC_PSEUDO_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandatomicpseudoinsts-cpp">LoongArchExpandAtomicPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a077940e3e1e5a3d29ea3ccd280b16c7c">llvm::createLoongArchExpandAtomicPseudoPass</a>, <a href="#ac00ca0d43e48b3ee7160cf6729ec3556">LoongArch_EXPAND_ATOMIC_PSEUDO_NAME</a> and <a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandatomicpseudoinsts-cpp-/loongarchexpandatomicpseudo/#a76f4448487bbc129d73f0b9cbaf314e8">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::LoongArchExpandAtomicPseudo::LoongArchExpandAtomicPseudo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LoongArch\_EXPAND\_ATOMIC\_PSEUDO\_NAME {#ac00ca0d43e48b3ee7160cf6729ec3556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LoongArch_EXPAND_ATOMIC_PSEUDO_NAME&nbsp;&nbsp;&nbsp;  "LoongArch atomic <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandatomicpseudoinsts-cpp">LoongArchExpandAtomicPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loongarchexpandatomicpseudoinsts-cpp-/loongarchexpandatomicpseudo/#a244f867320ac5c0848baa4575dc84446">anonymous{LoongArchExpandAtomicPseudoInsts.cpp}::LoongArchExpandAtomicPseudo::getPassName</a> and <a href="#aa92d56fda40328eb8068ec5b0591c1ef">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
