---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsselectiondaginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsSelectionDAGInfo` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MipsSelectionDAGInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-h">Target/Mips/MipsSelectionDAGInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo">SelectionDAGTargetInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets can subclass this to parameterize the <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> lowering and instruction selection process. <a href="/web-llvm/docs/api/classes/llvm/selectiondagtargetinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a9d3d42f13a383a444dc6ffc986d2bf">~MipsSelectionDAGInfo</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d61e8b4d21828b9057310e60078ebf">isTargetMemoryOpcode</a> (unsigned Opcode) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a node with the given target-specific opcode has a memory operand. <a href="#ac3d61e8b4d21828b9057310e60078ebf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-h">MipsSelectionDAGInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~MipsSelectionDAGInfo() {#a7a9d3d42f13a383a444dc6ffc986d2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsSelectionDAGInfo::~MipsSelectionDAGInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-h">MipsSelectionDAGInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isTargetMemoryOpcode() {#ac3d61e8b4d21828b9057310e60078ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsSelectionDAGInfo::isTargetMemoryOpcode (unsigned Opcode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if a node with the given target-specific opcode has a memory operand.</p>


<p>Nodes with such opcodes can only be created with <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ae6cc63109335eefe2c5727d1e12fc820">SelectionDAG::getMemIntrinsicNode</a></span>.</p>


<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-h">MipsSelectionDAGInfo.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-cpp">MipsSelectionDAGInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba5b6a508b5e09e0634a4110883b0784dc">llvm::MipsISD::FIRST_MEMORY_OPCODE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mipsisd/#a422daf9aa810935178671306b651d69ba54ba77ed9c65e892eb951e3142bd63d7">llvm::MipsISD::LAST_MEMORY_OPCODE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-cpp">MipsSelectionDAGInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsselectiondaginfo-h">MipsSelectionDAGInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
