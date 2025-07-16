---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mibundlebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MIBundleBuilder` Class Reference

<p>Helper class for constructing bundles of MachineInstrs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MIBundleBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95f533dbc9259810abdfe1b01225abbd">MIBundleBuilder</a> (MachineBasicBlock &amp;BB, MachineBasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> that inserts instructions into a new bundle in BB above the bundle or instruction at Pos. <a href="#a95f533dbc9259810abdfe1b01225abbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90723ad646bc8473311eb8cbf7a19698">MIBundleBuilder</a> (MachineBasicBlock &amp;BB, MachineBasicBlock::iterator B, MachineBasicBlock::iterator E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a bundle from the sequence of instructions between B and E. <a href="#a90723ad646bc8473311eb8cbf7a19698">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d1c198f2d3cc0e6030a27a656c138e">MIBundleBuilder</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> representing an existing instruction or bundle that has MI as its head. <a href="#ad7d1c198f2d3cc0e6030a27a656c138e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa885a1fbce293df7986792d6b83d2a97">getMBB</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the basic block containing this bundle. <a href="#aa885a1fbce293df7986792d6b83d2a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab25a34dd8ecbb5e4b8f9f00def3c1b3f">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if no instructions have been inserted in this bundle yet. <a href="#ab25a34dd8ecbb5e4b8f9f00def3c1b3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e65fa50b984d52c85101caf001e543">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator to the first bundled instruction. <a href="#a43e65fa50b984d52c85101caf001e543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e9378f3ad62f826d8ae046a219065d">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator beyond the last bundled instruction. <a href="#a09e9378f3ad62f826d8ae046a219065d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a15221a192683c58b5998fa42756ea">insert</a> (MachineBasicBlock::instr_iterator I, MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert MI into this bundle before I which must point to an instruction in the bundle, or <a href="#a09e9378f3ad62f826d8ae046a219065d">end()</a>. <a href="#aa4a15221a192683c58b5998fa42756ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1766e595101d7ff0b55ca62474c0e76">prepend</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert MI into MBB by prepending it to the instructions in the bundle. <a href="#ab1766e595101d7ff0b55ca62474c0e76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c15d55cada45b3ba4ec4ba5560c39c4">append</a> (MachineInstr *MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert MI into MBB by appending it to the instructions in the bundle. <a href="#a6c15d55cada45b3ba4ec4ba5560c39c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fde410e4375eafdb807fa47073f7176">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f6a3acfd26c8c62cb58d48b37cb4cd">Begin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a298872f3f24554a786b0917c3f23348a">End</a></td>
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

<p>Helper class for constructing bundles of MachineInstrs.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> can create a bundle from scratch by inserting new MachineInstrs one at a time, or it can create a bundle from a sequence of existing MachineInstrs in a basic block.</p>


<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MIBundleBuilder() {#a95f533dbc9259810abdfe1b01225abbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIBundleBuilder::MIBundleBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Pos)</td>
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

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> that inserts instructions into a new bundle in BB above the bundle or instruction at Pos.</p>

<p>Definition at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="#a6c15d55cada45b3ba4ec4ba5560c39c4">append</a>, <a href="#aa4a15221a192683c58b5998fa42756ea">insert</a> and <a href="#ab1766e595101d7ff0b55ca62474c0e76">prepend</a>.</p>

</div>
</div>

### MIBundleBuilder() {#a90723ad646bc8473311eb8cbf7a19698}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIBundleBuilder::MIBundleBuilder (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> B, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> E)</td>
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

<p>Create a bundle from the sequence of instructions between B and E.</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### MIBundleBuilder() {#ad7d1c198f2d3cc0e6030a27a656c138e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MIBundleBuilder::MIBundleBuilder (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/classes/llvm/mibundlebuilder">MIBundleBuilder</a> representing an existing instruction or bundle that has MI as its head.</p>

<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2b7ecbdbe9013ca2794761934d2bd9">llvm::getBundleEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### append() {#a6c15d55cada45b3ba4ec4ba5560c39c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIBundleBuilder &amp; llvm::MIBundleBuilder::append (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Insert MI into MBB by appending it to the instructions in the bundle.</p>


<p>MI will become the last instruction in the bundle.</p>


<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a09e9378f3ad62f826d8ae046a219065d">end</a>, <a href="#aa4a15221a192683c58b5998fa42756ea">insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a95f533dbc9259810abdfe1b01225abbd">MIBundleBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsdelayslotfiller-cpp/#ae81db0a0dba5fef75c1e6264aec87b3d">for</a>.</p>

</div>
</div>

### begin() {#a43e65fa50b984d52c85101caf001e543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator llvm::MIBundleBuilder::begin ()</td>
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

<p>Return an iterator to the first bundled instruction.</p>

<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a1271e8babb762355bcb15d461f8f6a1c">llvm::SITargetLowering::bundleInstWithWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a864a107b54979b53706e9d88f51c07e3">llvm::SIInstrInfo::expandPostRAPseudo</a> and <a href="#ab1766e595101d7ff0b55ca62474c0e76">prepend</a>.</p>

</div>
</div>

### empty() {#ab25a34dd8ecbb5e4b8f9f00def3c1b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MIBundleBuilder::empty ()</td>
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

<p>Return true if no instructions have been inserted in this bundle yet.</p>


<p>Empty bundles aren't representable in a <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a>.</p>


<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="#aa4a15221a192683c58b5998fa42756ea">insert</a>.</p>

</div>
</div>

### end() {#a09e9378f3ad62f826d8ae046a219065d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator llvm::MIBundleBuilder::end ()</td>
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

<p>Return an iterator beyond the last bundled instruction.</p>

<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>Referenced by <a href="#a6c15d55cada45b3ba4ec4ba5560c39c4">append</a>.</p>

</div>
</div>

### getMBB() {#aa885a1fbce293df7986792d6b83d2a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock &amp; llvm::MIBundleBuilder::getMBB ()</td>
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

<p>Return a reference to the basic block containing this bundle.</p>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

### insert() {#aa4a15221a192683c58b5998fa42756ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIBundleBuilder &amp; llvm::MIBundleBuilder::insert (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab6395548cae73865213e279ae461db54">MachineBasicBlock::instr_iterator</a> I, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Insert MI into this bundle before I which must point to an instruction in the bundle, or <a href="#a09e9378f3ad62f826d8ae046a219065d">end()</a>.</p>

<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a9a9e5ef20669b2c9666b2689808b48ee">llvm::MachineInstr::BundledPred</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518ad00e31da3877ce738df8343edcff6ed8">llvm::MachineInstr::BundledSucc</a>, <a href="#ab25a34dd8ecbb5e4b8f9f00def3c1b3f">empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#aa4a15221a192683c58b5998fa42756ea">insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a95f533dbc9259810abdfe1b01225abbd">MIBundleBuilder</a>.</p>


<p>Referenced by <a href="#a6c15d55cada45b3ba4ec4ba5560c39c4">append</a>, <a href="#aa4a15221a192683c58b5998fa42756ea">insert</a> and <a href="#ab1766e595101d7ff0b55ca62474c0e76">prepend</a>.</p>

</div>
</div>

### prepend() {#ab1766e595101d7ff0b55ca62474c0e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MIBundleBuilder &amp; llvm::MIBundleBuilder::prepend (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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

<p>Insert MI into MBB by prepending it to the instructions in the bundle.</p>


<p>MI will become the first instruction in the bundle.</p>


<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>


<p>References <a href="#a43e65fa50b984d52c85101caf001e543">begin</a>, <a href="#aa4a15221a192683c58b5998fa42756ea">insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="#a95f533dbc9259810abdfe1b01225abbd">MIBundleBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Begin {#af2f6a3acfd26c8c62cb58d48b37cb4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator llvm::MIBundleBuilder::Begin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

### End {#a298872f3f24554a786b0917c3f23348a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock::instr_iterator llvm::MIBundleBuilder::End</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

### MBB {#a8fde410e4375eafdb807fa47073f7176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock&amp; llvm::MIBundleBuilder::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">MachineInstrBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
