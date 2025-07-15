---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SSAUpdaterTraits` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd">SSAUpdaterTraits&lt;MachineSSAUpdater&gt;</a> - Traits for the <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl">SSAUpdaterImpl</a> template, specialized for <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SSAUpdaterTraits&lt;MachineSSAUpdater&gt; { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0802c5987a9f563867a25fd86adf5fb">BlkT</a> = <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ca6e0d8bb8c349b051ce63b2fcfb3e">ValT</a> = <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365bf8a96b6fbc950fdb77cc2d36f8e8">PhiT</a> = <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b11fa5130ad755ede0fc2d2a508cf5">BlkSucc_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a9936e11d7a6149f7cac8fa32a81dd488">MachineBasicBlock::succ_iterator</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a50b11fa5130ad755ede0fc2d2a508cf5">BlkSucc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d9ee2bf0883c64efbd9ec44d267599">BlkSucc_begin</a> (BlkT *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a50b11fa5130ad755ede0fc2d2a508cf5">BlkSucc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784a8e97960198712e1da4efd0e05553">BlkSucc_end</a> (BlkT *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-aafb8198284d925e7b2074b7152e40c8">PHI_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172ab6463bb885a8b2621054bb3330ae">PHI_begin</a> (PhiT *PHI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits/phi-iterator-aafb8198284d925e7b2074b7152e40c8">PHI_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa16ef06748b0b306b83535b94cb8f8">PHI_end</a> (PhiT *PHI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f0b89ac3af7c7b99a001b5c8eadff4">FindPredecessorBlocks</a> (MachineBasicBlock *BB, SmallVectorImpl&lt; MachineBasicBlock * &gt; *Preds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FindPredecessorBlocks - Put the predecessors of BB into the Preds vector. <a href="#a46f0b89ac3af7c7b99a001b5c8eadff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bb47729cc153812bf4c00989460022">GetPoisonVal</a> (MachineBasicBlock *BB, MachineSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetPoisonVal - Create an IMPLICIT_DEF instruction with a new register. <a href="#a55bb47729cc153812bf4c00989460022">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0db03d5e2c460331af4ee0afaaec953a">CreateEmptyPHI</a> (MachineBasicBlock *BB, unsigned NumPreds, MachineSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CreateEmptyPHI - Create a PHI instruction that defines a new register. <a href="#a0db03d5e2c460331af4ee0afaaec953a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f9292339308898a6ebf6021c35d3034">AddPHIOperand</a> (MachineInstr *PHI, Register Val, MachineBasicBlock *Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddPHIOperand - Add the specified value as an operand of the PHI for the specified predecessor block. <a href="#a9f9292339308898a6ebf6021c35d3034">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdf93bb5301f26cbddd2ff40548ca0f">InstrIsPHI</a> (MachineInstr *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>InstrIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an instruction is a PHI. <a href="#a5cdf93bb5301f26cbddd2ff40548ca0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b7b0b7ba267226509dfe6c2824951f">ValueIsPHI</a> (Register Val, MachineSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction that defines the specified register is a PHI instruction. <a href="#a54b7b0b7ba267226509dfe6c2824951f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a032cc4ff4828960913e831e32eb9f036">ValueIsNewPHI</a> (Register Val, MachineSSAUpdater *Updater)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValueIsNewPHI - Like ValueIsPHI but also check if the PHI has no source operands, i.e., it was just added. <a href="#a032cc4ff4828960913e831e32eb9f036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253173e83f9dfeafd7e3d2fd5e57f999">GetPHIValue</a> (MachineInstr *PHI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetPHIValue - For the specified PHI instruction, return the register that it defines. <a href="#a253173e83f9dfeafd7e3d2fd5e57f999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-4e613f36227a2a352217431a8f1958cd">SSAUpdaterTraits&lt;MachineSSAUpdater&gt;</a> - Traits for the <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl">SSAUpdaterImpl</a> template, specialized for <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a>.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BlkSucc\_iterator {#a50b11fa5130ad755ede0fc2d2a508cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::BlkSucc_iterator =  MachineBasicBlock::succ_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

### BlkT {#aa0802c5987a9f563867a25fd86adf5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::BlkT =  MachineBasicBlock</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

### PhiT {#a365bf8a96b6fbc950fdb77cc2d36f8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::PhiT =  MachineInstr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

### ValT {#ad5ca6e0d8bb8c349b051ce63b2fcfb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::ValT =  Register</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AddPHIOperand() {#a9f9292339308898a6ebf6021c35d3034}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::AddPHIOperand (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * PHI, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Pred)</td>
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

<p>AddPHIOperand - Add the specified value as an operand of the PHI for the specified predecessor block.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#abf1febf2a98f588146548a3a485d3838">llvm::MachineInstrBuilder::addMBB</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### BlkSucc\_begin() {#a74d9ee2bf0883c64efbd9ec44d267599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlkSucc_iterator llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::BlkSucc_begin (<a href="#aa0802c5987a9f563867a25fd86adf5fb">BlkT</a> * BB)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a6321b189ea8fd5058663f8a87d6c23e9">llvm::MachineBasicBlock::succ_begin</a>.</p>

</div>
</div>

### BlkSucc\_end() {#a784a8e97960198712e1da4efd0e05553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlkSucc_iterator llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::BlkSucc_end (<a href="#aa0802c5987a9f563867a25fd86adf5fb">BlkT</a> * BB)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3ddd708642d60c1661992ff8ba1b215d">llvm::MachineBasicBlock::succ_end</a>.</p>

</div>
</div>

### CreateEmptyPHI() {#a0db03d5e2c460331af4ee0afaaec953a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::CreateEmptyPHI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, unsigned NumPreds, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> * Updater)</td>
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

<p>CreateEmptyPHI - Create a PHI instruction that defines a new register.</p>


<p>Add it into the specified block and return the register.</p>


<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a095ce2d870dadf620a4c887ecc0efef8">llvm::MachineBasicBlock::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a18679ba04ac07baa9c502ce555b48859">InsertNewDef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### FindPredecessorBlocks() {#a46f0b89ac3af7c7b99a001b5c8eadff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::FindPredecessorBlocks (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * &gt; * Preds)</td>
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

<p>FindPredecessorBlocks - Put the predecessors of BB into the Preds vector.</p>

<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a> and <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#addd80df79ba902914c7d8a52e3896b79">llvm::MachineBasicBlock::predecessors</a>.</p>

</div>
</div>

### GetPHIValue() {#a253173e83f9dfeafd7e3d2fd5e57f999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::GetPHIValue (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * PHI)</td>
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

<p>GetPHIValue - For the specified PHI instruction, return the register that it defines.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### GetPoisonVal() {#a55bb47729cc153812bf4c00989460022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::GetPoisonVal (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> * Updater)</td>
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

<p>GetPoisonVal - Create an IMPLICIT_DEF instruction with a new register.</p>


<p>Add it into the specified block and return the register.</p>


<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa7dc7faaab4856b8f0014b8283e26c7b">llvm::MachineBasicBlock::getFirstNonPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp/#a18679ba04ac07baa9c502ce555b48859">InsertNewDef</a>.</p>

</div>
</div>

### InstrIsPHI() {#a5cdf93bb5301f26cbddd2ff40548ca0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::InstrIsPHI (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * I)</td>
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

<p>InstrIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an instruction is a PHI.</p>

<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a54b7b0b7ba267226509dfe6c2824951f">ValueIsPHI</a>.</p>

</div>
</div>

### PHI\_begin() {#a172ab6463bb885a8b2621054bb3330ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHI_iterator llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::PHI_begin (<a href="#a365bf8a96b6fbc950fdb77cc2d36f8e8">PhiT</a> * PHI)</td>
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



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### PHI\_end() {#abaa16ef06748b0b306b83535b94cb8f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PHI_iterator llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::PHI_end (<a href="#a365bf8a96b6fbc950fdb77cc2d36f8e8">PhiT</a> * PHI)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>

</div>
</div>

### ValueIsNewPHI() {#a032cc4ff4828960913e831e32eb9f036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::ValueIsNewPHI (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> * Updater)</td>
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

<p>ValueIsNewPHI - Like ValueIsPHI but also check if the PHI has no source operands, i.e., it was just added.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a> and <a href="#a54b7b0b7ba267226509dfe6c2824951f">ValueIsPHI</a>.</p>

</div>
</div>

### ValueIsPHI() {#a54b7b0b7ba267226509dfe6c2824951f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr * llvm::SSAUpdaterTraits&lt; MachineSSAUpdater &gt;::ValueIsPHI (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Val, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater">MachineSSAUpdater</a> * Updater)</td>
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

<p>ValueIsPHI - <a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction that defines the specified register is a PHI instruction.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a40d954b9cf9ee8b545a78725f2549cba">llvm::MachineRegisterInfo::getVRegDef</a> and <a href="#a5cdf93bb5301f26cbddd2ff40548ca0f">InstrIsPHI</a>.</p>


<p>Referenced by <a href="#a032cc4ff4828960913e831e32eb9f036">ValueIsNewPHI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinessaupdater-cpp">MachineSSAUpdater.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
