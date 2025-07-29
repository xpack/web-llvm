---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bittracker/registerref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RegisterRef` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::BitTracker::RegisterRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">Target/Hexagon/BitTracker.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fad6ac0e35685dda5d6ad620d77d745">RegisterRef</a> (Register R=0, unsigned S=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b58b6c65a511d8dec193cf8ff3cd057">RegisterRef</a> (const MachineOperand &amp;MO)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83d460802fba9c074af90710d239f516">Reg</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd26bd676aebea77891d6d204dd804d5">Sub</a></td>
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


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterRef() {#a2fad6ac0e35685dda5d6ad620d77d745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::RegisterRef::RegisterRef (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> R=0, unsigned S=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="#a83d460802fba9c074af90710d239f516">Reg</a> and <a href="#afd26bd676aebea77891d6d204dd804d5">Sub</a>.</p>

</div>
</div>

### RegisterRef() {#a6b58b6c65a511d8dec193cf8ff3cd057}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BitTracker::RegisterRef::RegisterRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#a15b5b86944f6df97d2c3659d77f51f91">getReg</a>, <a href="#a83d460802fba9c074af90710d239f516">Reg</a> and <a href="#afd26bd676aebea77891d6d204dd804d5">Sub</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Reg {#a83d460802fba9c074af90710d239f516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::BitTracker::RegisterRef::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a1366c4865d7c8ca31dcf403406e3b291">llvm::BitTracker::MachineEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8e3ebf47bfdde7c6ce8235ca71190e1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getFinalVRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a645204801c7cc2848635065d0331dffd">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getSubregMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#adf3ae590ab5d562772498428b6ad8e60">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::isTransparentCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/bitsimplification/#a7ae2252105ba3f43b639d6648a219a85">anonymous{HexagonBitSimplify.cpp}::BitSimplification::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/copygeneration/#add974c22e80e417ae81566ae9ed683a6">anonymous{HexagonBitSimplify.cpp}::CopyGeneration::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/redundantinstrelimination/#a6221dbe4d8c107be3f19ca24c760f921">anonymous{HexagonBitSimplify.cpp}::RedundantInstrElimination::processBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8944fc547212f985ad3f9706eb5b8725">llvm::BitTracker::MachineEvaluator::putCell</a>, <a href="#a6b58b6c65a511d8dec193cf8ff3cd057">RegisterRef</a>, <a href="#a2fad6ac0e35685dda5d6ad620d77d745">RegisterRef</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/#aa073e141f102376e7e3965f39436c70f">llvm::BitTracker::subst</a>.</p>

</div>
</div>

### Sub {#afd26bd676aebea77891d6d204dd804d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BitTracker::RegisterRef::Sub</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a1366c4865d7c8ca31dcf403406e3b291">llvm::BitTracker::MachineEvaluator::evaluate</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a9a70d4969d8d43a9c9b324f692bc8ecd">llvm::BitTracker::MachineEvaluator::getCell</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8e3ebf47bfdde7c6ce8235ca71190e1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getFinalVRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a64ee9ca87205e764e0382240030f87ee">llvm::BitTracker::MachineEvaluator::getRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a645204801c7cc2848635065d0331dffd">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getSubregMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/copygeneration/#add974c22e80e417ae81566ae9ed683a6">anonymous{HexagonBitSimplify.cpp}::CopyGeneration::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/redundantinstrelimination/#a6221dbe4d8c107be3f19ca24c760f921">anonymous{HexagonBitSimplify.cpp}::RedundantInstrElimination::processBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/machineevaluator/#a8944fc547212f985ad3f9706eb5b8725">llvm::BitTracker::MachineEvaluator::putCell</a>, <a href="#a6b58b6c65a511d8dec193cf8ff3cd057">RegisterRef</a>, <a href="#a2fad6ac0e35685dda5d6ad620d77d745">RegisterRef</a> and <a href="/web-llvm/docs/api/structs/llvm/bittracker/#aa073e141f102376e7e3965f39436c70f">llvm::BitTracker::subst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/bittracker-h">BitTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
