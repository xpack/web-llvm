---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-combinerhelper-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{CombinerHelper.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{CombinerHelper.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/preferredtuple">PreferredTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7d81ffe276a47a4226c0f9ee75575f9">ChoosePreferredUse</a> (MachineInstr &amp;LoadMI, PreferredTuple &amp;CurrentUse, const LLT TyForCandidate, unsigned OpcodeForCandidate, MachineInstr *MIForCandidate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select a preference between two uses. <a href="#af7d81ffe276a47a4226c0f9ee75575f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe36a8462243713bdada68a3fc16ee47">InsertInsnsWithoutSideEffectsBeforeUse</a> (MachineIRBuilder &amp;Builder, MachineInstr &amp;DefMI, MachineOperand &amp;UseMO, std::function&lt; void(MachineBasicBlock *, MachineBasicBlock::iterator, MachineOperand &amp;UseMO)&gt; Inserter)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find a suitable place to insert some instructions and insert them. <a href="#abe36a8462243713bdada68a3fc16ee47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### ChoosePreferredUse() {#af7d81ffe276a47a4226c0f9ee75575f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreferredTuple anonymous{CombinerHelper.cpp}::ChoosePreferredUse (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; LoadMI, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple">PreferredTuple</a> &amp; CurrentUse, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/llt">LLT</a> TyForCandidate, unsigned OpcodeForCandidate, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MIForCandidate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select a preference between two uses.</p>


<p>CurrentUse is the current preference while *ForCandidate is attributes of the candidate under consideration.</p>


<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="#af7d81ffe276a47a4226c0f9ee75575f9">ChoosePreferredUse</a>, <a href="/web-llvm/docs/api/structs/llvm/preferredtuple/#ae846809b677f5cc759c2360d3fceed3a">llvm::PreferredTuple::ExtendOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a956ffd0de93798f523683b447646dd92">llvm::LLT::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a69fb30748f1b3e8a0affd486a9f59f6d">llvm::LLT::isValid</a> and <a href="/web-llvm/docs/api/structs/llvm/preferredtuple/#a1b183e97d50ba4c09e23118f4075fda5">llvm::PreferredTuple::Ty</a>.</p>


<p>Referenced by <a href="#af7d81ffe276a47a4226c0f9ee75575f9">ChoosePreferredUse</a>.</p>

</div>
</div>

### InsertInsnsWithoutSideEffectsBeforeUse() {#abe36a8462243713bdada68a3fc16ee47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CombinerHelper.cpp}::InsertInsnsWithoutSideEffectsBeforeUse (<a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; DefMI, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; UseMO, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp;UseMO)&gt; Inserter)</td>
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

<p>Find a suitable place to insert some instructions and insert them.</p>


<p>This function accounts for special cases like inserting before a PHI node. The current strategy for inserting before PHI's is to duplicate the instructions for each predecessor. However, while that's ok for G_TRUNC on most targets since it generally requires no code, other targets/cases may want to try harder to find a dominating block.</p>


<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7dc7faaab4856b8f0014b8283e26c7b">llvm::MachineBasicBlock::getFirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a57e64b633278df75c699e6b98ce15031">llvm::MachineOperand::getMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9719077fcba2cd439e84897257a47bb0">llvm::MachineOperand::getParent</a>, <a href="#abe36a8462243713bdada68a3fc16ee47">InsertInsnsWithoutSideEffectsBeforeUse</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#abe36a8462243713bdada68a3fc16ee47">InsertInsnsWithoutSideEffectsBeforeUse</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/combinerhelper-cpp">CombinerHelper.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
