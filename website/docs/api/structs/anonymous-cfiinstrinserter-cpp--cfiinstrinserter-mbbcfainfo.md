---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-cfiinstrinserter-cpp-/cfiinstrinserter/mbbcfainfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MBBCFAInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2f0b274460b934dfa264aa7be0d4505">MBB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871b0ebf4b95d2a8b861f13e00ddb36a">IncomingCFAOffset</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa offset valid at basic block entry. <a href="#a871b0ebf4b95d2a8b861f13e00ddb36a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1419d7576c9778d7d7f9d7e399c8d64f">OutgoingCFAOffset</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa offset valid at basic block exit. <a href="#a1419d7576c9778d7d7f9d7e399c8d64f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607a28d85ced9f3d96fd2d93f25aec31">IncomingCFARegister</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa register valid at basic block entry. <a href="#a607a28d85ced9f3d96fd2d93f25aec31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a555ae7c5dd5ef0827282ac0589b3f5">OutgoingCFARegister</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa register valid at basic block exit. <a href="#a6a555ae7c5dd5ef0827282ac0589b3f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534f37116d6400ba6848f85dd9f02de4">IncomingCSRSaved</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of callee saved registers saved at basic block entry. <a href="#a534f37116d6400ba6848f85dd9f02de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ca18ac19c4faf8c0f6a53d9e11e263">OutgoingCSRSaved</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set of callee saved registers saved at basic block exit. <a href="#a17ca18ac19c4faf8c0f6a53d9e11e263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998ba4f5677ae23881fbcd7e2de97c34">Processed</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If in/out cfa offset and register values for this block have already been set or not. <a href="#a998ba4f5677ae23881fbcd7e2de97c34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### IncomingCFAOffset {#a871b0ebf4b95d2a8b861f13e00ddb36a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::IncomingCFAOffset = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa offset valid at basic block entry.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### IncomingCFARegister {#a607a28d85ced9f3d96fd2d93f25aec31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::IncomingCFARegister = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa register valid at basic block entry.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### IncomingCSRSaved {#a534f37116d6400ba6848f85dd9f02de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::IncomingCSRSaved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of callee saved registers saved at basic block entry.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### MBB {#af2f0b274460b934dfa264aa7be0d4505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::MBB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### OutgoingCFAOffset {#a1419d7576c9778d7d7f9d7e399c8d64f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::OutgoingCFAOffset = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa offset valid at basic block exit.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### OutgoingCFARegister {#a6a555ae7c5dd5ef0827282ac0589b3f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::OutgoingCFARegister = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> of cfa register valid at basic block exit.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### OutgoingCSRSaved {#a17ca18ac19c4faf8c0f6a53d9e11e263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitVector anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::OutgoingCSRSaved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set of callee saved registers saved at basic block exit.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

### Processed {#a998ba4f5677ae23881fbcd7e2de97c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CFIInstrInserter.cpp}::CFIInstrInserter::MBBCFAInfo::Processed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If in/out cfa offset and register values for this block have already been set or not.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/cfiinstrinserter-cpp">CFIInstrInserter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
