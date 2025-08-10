---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/vregrenamer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VRegRenamer` Class

<p><a href="/web-llvm/docs/api/classes/llvm/vregrenamer">VRegRenamer</a> - This class is used for renaming vregs in a machine basic block according to semantics of the instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::VRegRenamer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">CodeGen/MIRVRegNamerUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40e2165f07ee6464a85366f53b08e8f">VRegRenamer</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad424af22e00bb521388ec299c0a3cac7">VRegRenamer</a> (MachineRegisterInfo &amp;MRI)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0de3daa9030d33988e07804f9faa03a">renameVRegs</a> (MachineBasicBlock *MBB, unsigned BBNum)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as the above, but sets a BBNum depending on BB traversal that will be used as prefix for the vreg names. <a href="#ae0de3daa9030d33988e07804f9faa03a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679c893eebe76d49bae96b06cbf5b49a">getInstructionOpcodeHash</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, construct a hash of the operands of the instructions along with the opcode. <a href="#a679c893eebe76d49bae96b06cbf5b49a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98acfdcb080981ca02dff3ae19532892">getVRegRenameMap</a> (const std::vector&lt; NamedVReg &gt; &amp;VRegs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For all the VRegs that are candidates for renaming, return a mapping from old vregs to new vregs with names. <a href="#a98acfdcb080981ca02dff3ae19532892">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8320b631eaa9d19b6ce216907f3eee1">doVRegRenaming</a> (const std::map&lt; unsigned, unsigned &gt; &amp;VRegRenameMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform replacing of registers based on the &lt;old,new&gt; vreg map. <a href="#ab8320b631eaa9d19b6ce216907f3eee1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d6c0231b92c8422054117cb39b379f">createVirtualRegister</a> (unsigned VReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createVirtualRegister - Given an existing vreg, create a named vreg to take its place. <a href="#aa7d6c0231b92c8422054117cb39b379f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c015c0ada12ddf764529b71def15392">createVirtualRegisterWithLowerName</a> (unsigned VReg, StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a vreg with name and return it. <a href="#a1c015c0ada12ddf764529b71def15392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f460c69bb6bd8a7c1e77d1a11246303">renameInstsInMBB</a> (MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Linearly traverse the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> and rename each instruction's vreg definition based on the semantics of the instruction. <a href="#a3f460c69bb6bd8a7c1e77d1a11246303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9800de4cb415373abe969d8a0d03181">MRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2ea1658be8ad213b7dd39989939b45">CurrentBBNumber</a> = 0</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/vregrenamer">VRegRenamer</a> - This class is used for renaming vregs in a machine basic block according to semantics of the instruction.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VRegRenamer() {#ae40e2165f07ee6464a85366f53b08e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VRegRenamer::VRegRenamer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>.</p>

</div>
</div>

### VRegRenamer() {#ad424af22e00bb521388ec299c0a3cac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VRegRenamer::VRegRenamer (<a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### renameVRegs() {#ae0de3daa9030d33988e07804f9faa03a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VRegRenamer::renameVRegs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB, unsigned BBNum)</td>
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

<p>Same as the above, but sets a BBNum depending on BB traversal that will be used as prefix for the vreg names.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#a08d8c562daea622f17cb5ba28e7efb4c">runOnBasicBlock</a> and <a href="/web-llvm/docs/api/classes/anonymous-mirnamerpass-cpp-/mirnamer/#aa10d9a5cfb79a609801d4a4ac79e7b6d">anonymous{MIRNamerPass.cpp}::MIRNamer::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createVirtualRegister() {#aa7d6c0231b92c8422054117cb39b379f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned VRegRenamer::createVirtualRegister (unsigned VReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createVirtualRegister - Given an existing vreg, create a named vreg to take its place.</p>


<p>The name is determined by calling getInstructionOpcodeHash.</p>


<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>, definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a>.</p>

</div>
</div>

### createVirtualRegisterWithLowerName() {#a1c015c0ada12ddf764529b71def15392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned VRegRenamer::createVirtualRegisterWithLowerName (unsigned VReg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a vreg with name and return it.</p>

<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a>.</p>

</div>
</div>

### doVRegRenaming() {#ab8320b631eaa9d19b6ce216907f3eee1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VRegRenamer::doVRegRenaming (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; unsigned, unsigned &gt; &amp; VRegRenameMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform replacing of registers based on the &lt;old,new&gt; vreg map.</p>

<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a>.</p>

</div>
</div>

### getInstructionOpcodeHash() {#a679c893eebe76d49bae96b06cbf5b49a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string VRegRenamer::getInstructionOpcodeHash (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, construct a hash of the operands of the instructions along with the opcode.</p>


<p>When dealing with virtual registers, just hash the opcode of the instruction defining that vreg. Handle immediates, registers (physical and virtual) explicitly, and return a common value for the other cases. <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> will be named in the following scheme bb&lt;block_no&gt;<em>hash</em>&lt;collission_count&gt;.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a>.</p>

</div>
</div>

### getVRegRenameMap() {#a98acfdcb080981ca02dff3ae19532892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VRegRenameMap VRegRenamer::getVRegRenameMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; NamedVReg &gt; &amp; VRegs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For all the VRegs that are candidates for renaming, return a mapping from old vregs to new vregs with names.</p>

<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a>.</p>

</div>
</div>

### renameInstsInMBB() {#a3f460c69bb6bd8a7c1e77d1a11246303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VRegRenamer::renameInstsInMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Linearly traverse the <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> and rename each instruction's vreg definition based on the semantics of the instruction.</p>


<p>Names are as follows bb&lt;BBNum&gt;<em>hash</em>[0-9]+</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CurrentBBNumber {#a3b2ea1658be8ad213b7dd39989939b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::VRegRenamer::CurrentBBNumber = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>.</p>

</div>
</div>

### MRI {#ab9800de4cb415373abe969d8a0d03181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; llvm::VRegRenamer::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-cpp">MIRVRegNamerUtils.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/mirvregnamerutils-h">MIRVRegNamerUtils.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
