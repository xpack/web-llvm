---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AVRExpandPseudoInsts.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avr-h">AVR.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrinstrinfo-h">AVRInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrtargetmachine-h">AVRTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-h">MCTargetDesc/AVRMCTargetDesc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-avrexpandpseudoinsts-cpp-">anonymous{AVRExpandPseudoInsts.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo">AVRExpandPseudo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Expands "placeholder" instructions marked as pseudo into actual <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> instructions. <a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636eb49c556ccf27213b0a20028d4027">INITIALIZE_PASS</a> (AVRExpandPseudo, "avr-expand-pseudo", AVR_EXPAND_PSEUDO_NAME, false, false) namespace llvm</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977357d70c05cd350c98668b5a606acb">AVR_EXPAND_PSEUDO_NAME</a>&nbsp;&nbsp;&nbsp;"AVR <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bf4b164c71aa8d0faf7b8cc33c47d5">EXPAND</a>(Op)&nbsp;&nbsp;&nbsp;...</td>
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

### INITIALIZE\_PASS() {#a636eb49c556ccf27213b0a20028d4027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (AVRExpandPseudo, "avr-<a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>-pseudo", <a href="#a977357d70c05cd350c98668b5a606acb">AVR_EXPAND_PSEUDO_NAME</a>, false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2644 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="#a977357d70c05cd350c98668b5a606acb">AVR_EXPAND_PSEUDO_NAME</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo/#a3a9340f714a9e64a69b5fd17649a5fb2">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::AVRExpandPseudo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac9db8a217bf6de3f1f146577061705">llvm::createAVRExpandPseudoPass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### AVR\_EXPAND\_PSEUDO\_NAME {#a977357d70c05cd350c98668b5a606acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define AVR_EXPAND_PSEUDO_NAME&nbsp;&nbsp;&nbsp;"AVR <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchexpandpseudoinsts-cpp/#a31df8275bbc686a779424eb21ad67d5e">pseudo</a> instruction expansion pass"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo/#afb237cdadc124e2393a8bee54821108a">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::getPassName</a> and <a href="#a636eb49c556ccf27213b0a20028d4027">INITIALIZE_PASS</a>.</p>

</div>
</div>

### EXPAND {#a05bf4b164c71aa8d0faf7b8cc33c47d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EXPAND(Op)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Op:                                                                     \
    return <a href="/web-llvm/docs/api/files/lib/lib/support/globpattern-cpp/#a80bc10e949d0743241f5cdc2c75de52a">expand</a>&lt;Op&gt;(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>)
</div>
</dd>
</dl>

<p>Definition at line 2566 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab3547e3af4263fb24bac33b211aa07fb">llvm::X86TargetLowering::getTargetNodeName</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
