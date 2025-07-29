---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mibundleoperands
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MIBundleOperands` Class

<p><a href="/web-llvm/docs/api/classes/llvm/mibundleoperands">MIBundleOperands</a> - Iterate over all operands in a bundle of machine instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MIBundleOperands { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">llvm/CodeGen/MachineInstrBundle.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase">MIBundleOperandIteratorBase&lt;ValueT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase">MIBundleOperandIteratorBase</a> - Iterator that visits all operands in a bundle of MachineInstrs. <a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e2f783f344cee87f532fab9fb128f6">MIBundleOperands</a> (MachineInstr &amp;MI)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2aadb3f125380fe1b8fda2aa3ae5a0e">MIBundleOperands</a> (MachineBasicBlock::instr_iterator InstrE, MachineInstr::mop_iterator OpE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for an iterator past the last iteration. <a href="#ae2aadb3f125380fe1b8fda2aa3ae5a0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mibundleoperands">MIBundleOperands</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0325c5a8e1207d3922d1d031ecb06f5e">end</a> (const MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator past the last iteration. <a href="#a0325c5a8e1207d3922d1d031ecb06f5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/mibundleoperands">MIBundleOperands</a> - Iterate over all operands in a bundle of machine instructions.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIBundleOperands() {#a66e2f783f344cee87f532fab9fb128f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIBundleOperands::MIBundleOperands (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/mibundleoperanditeratorbase/#a1b29c8ad754c0dde5d71f1c9330f6773">llvm::MIBundleOperandIteratorBase&lt; MachineOperand &gt;::MIBundleOperandIteratorBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### MIBundleOperands() {#ae2aadb3f125380fe1b8fda2aa3ae5a0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIBundleOperands::MIBundleOperands (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> InstrE, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab5b1fcfd0e1eddba786fefcdf28f1689">MachineInstr::mop_iterator</a> OpE)</td>
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

<p>Constructor for an iterator past the last iteration.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### end() {#a0325c5a8e1207d3922d1d031ecb06f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIBundleOperands llvm::MIBundleOperands::end (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator past the last iteration.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad024c105627166503bab1ed0f47f71d9">llvm::mi_bundle_ops</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbundle-h">MachineInstrBundle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
